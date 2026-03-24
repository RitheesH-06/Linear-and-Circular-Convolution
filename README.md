# EXP 1 : Linear and Circular Convolution

## AIM: 

 To perform Linear and Circular Convolution for two given sequence using SCILAB. 

## APPARATUS REQUIRED: 
PC installed with SCILAB. 

## PROGRAM

### LINEAR CONVOLUTION
```
clc;
clear;
close;

// Given sequences
x = [3 2 1 2];
h = [1 2 1 2];

// Linear Convolution
y_linear = convol(x, h);

// Display result
disp("Linear Convolution Result:");
disp(y_linear);

// Time index
n = 0:length(y_linear)-1;

// Plot using plot2d3() for discrete signal
figure;
plot2d3(n, y_linear);
xlabel("n");
ylabel("Amplitude");
title("Linear Convolution of x(n) and h(n)");
```

### CIRCULAR CONVOLUTION

```
clc;
clear;
close;

// Given sequences
x = [3 2 1 2];
h = [1 2 1 2];

// Linear Convolution
y_linear = convol(x, h);

// Display result
disp("Linear Convolution Result:");
disp(y_linear);

// Time index
n = 0:length(y_linear)-1;

// Plot using plot2d3() for discrete signal
figure;
plot2d3(n, y_linear);
xlabel("n");
ylabel("Amplitude");
title("Linear Convolution of x(n) and h(n)");
```

## OUTPUT (Linear Convolution): 

<img width="1546" height="787" alt="image" src="https://github.com/user-attachments/assets/83447032-b6aa-44d1-a3d2-3c94bf4ae209" />

## OUTPUT (Circular Convolution): 

<img width="1590" height="791" alt="image" src="https://github.com/user-attachments/assets/041c44b1-a9a2-4395-9e55-4c33064d2443" />

## RESULT: 

Linear and circular convolution of the sequences were successfully performed in SCILAB and The results were plotted.
