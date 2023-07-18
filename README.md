# Function_Plotter

The Function Plotter is a Python program that allows you to plot any user-defined mathematical function on a graph. It uses the matplotlib library to generate the plot.

## Usage
To use the Function Plotter, simply create an instance of the Function_Plotter class and enter the function, minimum value of x, and maximum value of x when prompted:

**Python code**
<br>
<code>from function_plotter import Function_Plotter
a = Function_Plotter()</code>
<br>
<br>
This will prompt you to enter the mathematical function that you want to plot, as well as the minimum and maximum values of the x-axis.

After entering the function and the axis values, the plot will be generated and displayed.

## Features
<ul>
        <li>Allows you to plot any user-defined mathematical function on a graph.</li>
        <li>Validates the user input to ensure that the function is in the correct format.</li>
        <li>Generates a plot using the matplotlib library.</li>
        <li>Provides a user-friendly interface for easy input and output.</li>
</ul>


## Example
Here's an example of how to use the Function Plotter to plot the function y = x^2 over the range x = -10 to x = 10:

**Python code**
<br>
<code>from function_plotter import Function_Plotter
a = Function_Plotter()</code>
<br>
<br>
Enter the function x**2 in the prompt for "Enter function of x:"<br>
Enter -10 in the prompt for "Enter Min value of x:"<br>
Enter 10 in the prompt for "Enter Max value of x:"

The plot of y = x^2 over the range x = -10 to x = 10 will be displayed.

## Feedback
If you have any feedback or suggestions for improving the Function Plotter, please create an issue on the GitHub repository or contact me directly.
