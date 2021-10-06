# Programming Assignment: Linear Regression

## ex1

Diagonal Matrix<br>

   1   0   0   0   0 <br>
   0   1   0   0   0<br>
   0   0   1   0   0<br>
   0   0   0   1   0<br>
   0   0   0   0   1<br>

Program paused. Press enter to continue.<br>
Plotting Data ...<br>

![image-20211006175846009](./pic/image-20211006175846009.png)

Program paused. Press enter to continue.<br>

Testing the cost function ...<br><br>
With theta = [0 ; 0]<br>
Cost computed = 32.072734<br>
Expected cost value (approx) 32.07<br>

With theta = [-1 ; 2]<br>
Cost computed = 54.242455<br>
Expected cost value (approx) 54.24<br>
Program paused. Press enter to continue.<br>

Running Gradient Descent ...<br>
Theta found by gradient descent:<br>
-3.630291<br>
1.166362<br>
Expected theta values (approx)<br>
 -3.6303<br>
  1.1664<br>

For population = 35,000, we predict a profit of 4519.767868<br>
For population = 70,000, we predict a profit of 45342.450129<br>
Program paused. Press enter to continue.<br>

Visualizing J(theta_0, theta_1) ...<br>

![image-20211006180021220](./pic/image-20211006180021220.png)

![image-20211006180044253](./pic/image-20211006180044253.png)

![image-20211006180053458](./pic/image-20211006180053458.png)

## ex1_mulit 

 Loading data ...<br>
First 10 examples from the dataset:<br>
 x = [2104 3], y = 399900<br>
 x = [1600 3], y = 329900<br>
 x = [2400 3], y = 369000<br>
 x = [1416 2], y = 232000<br>
 x = [3000 4], y = 539900<br>
 x = [1985 4], y = 299900<br>
 x = [1534 3], y = 314900<br>
 x = [1427 3], y = 198999<br>
 x = [1380 3], y = 212000<br>
 x = [1494 3], y = 242500<br>
Program paused. Press enter to continue.<br>
Normalizing Features ...<br>
Running gradient descent ...<br>

![image-20211006185535408](./pic/image-20211006185535408.png)
Theta computed from gradient descent:<br>
 334302.063993<br>
 100087.116006<br>
 3673.548451<br>

Predicted price of a 1650 sq-ft, 3 br house (using gradient descent):<br>
 $289314.620338<br>
Program paused. Press enter to continue.<br>
Solving with normal equations...<br>
Theta computed from the normal equations:<br>
 89597.909543<br>
 139.210674<br>
 -8738.019112<br>

Predicted price of a 1650 sq-ft, 3 br house (using normal equations):<br>
 $293081.464335<br>



## submit result

==
==                                   Part Name |     Score | Feedback
==                                   --------- |     ----- | --------
==                            Warm-up Exercise |  10 /  10 | Nice work!
==           Computing Cost (for One Variable) |  40 /  40 | Nice work!
==         Gradient Descent (for One Variable) |  50 /  50 | Nice work!
==                       Feature Normalization |   0 /   0 | Nice work!
==     Computing Cost (for Multiple Variables) |   0 /   0 | Nice work!
==   Gradient Descent (for Multiple Variables) |   0 /   0 | Nice work!
==                            Normal Equations |   0 /   0 | Nice work!
