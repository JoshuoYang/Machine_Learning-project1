ML Homework1

Description :
Please write a program that can do regularized linear model regression (polynomial basis) and
visualization.
You should do it by both LSE and Newton's method.
Input parameters:
1. the path and name of a file which consists of data points (comma seperated: x,y):
2. the number of polynomial bases n.
3. lambda (only for LSE case)
Program Behavior: For example, if the number of bases is set to 3, it means that the program
is going to find a curve that best fits the data points by
Required functions:
a. For LSE:
1. Use LU decomposition to find the inverse of , Gauss-Jordan
elimination will also be accepted.(A is the design matrix).
2. Print out the equation of the best fitting line and the error.
b. For Newton's method:
1. Please use the method mentioned in the lesson.
2. Print out the equation of the best fitting line and the error, and compare to LSE.
c. For visualization:
1. Please visualize the data points which are the input of program, and the best
fitting curve.
2. It's free to use any existing package.
