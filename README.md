# Logistic-Regression
## Sigmoid Function Implementation and Visualization
This code snippet demonstrates the implementation and visualization of the sigmoid function, a key component in logistic regression. The sigmoid function takes an input 
𝑧
z and outputs a value between 0 and 1, representing the probability of a binary outcome.

## Exponential Calculation and Sigmoid Function Definition
The code begins by computing the exponential of an array of values ranging from -10 to 10 using the NumPy exp function, showcasing how the sigmoid function can handle arrays as inputs. It also calculates the sigmoid of a single scalar value (1), demonstrating its versatility.

Next, the sigmoid function is defined, which applies the sigmoid transformation to the input 
𝑧
z. This function utilizes the formula 
𝑔
(
𝑧
)
=
1
1
+
𝑒
−
𝑧
g(z)= 
1+e 
−z
 
1
​
 , where 
𝑒
e is the base of the natural logarithm.

## Visualization of Sigmoid Function
The sigmoid function is then applied to an array of evenly spaced values between -10 and 10, and the resulting sigmoid values are plotted against the input values 
𝑧
z. The plot illustrates the characteristic S-shaped curve of the sigmoid function, showcasing how it transforms input values into probabilities.

Additionally, the plt_one_addpt_onclick function is imported, enabling users to interactively add new data points to the plot by clicking on the figure. This feature facilitates the exploration of how the sigmoid function responds to changes in input data, providing a dynamic visualization of its behavior.

Overall, this code snippet serves as a practical demonstration of the sigmoid function and its application in logistic regression.


## Plot of Sigmoid Function
![Sigmoid-Function-plot](https://github.com/UMMY87/Logistic-Regression/assets/117314436/35282501-499c-4e85-82ec-e46a23e6c518)
