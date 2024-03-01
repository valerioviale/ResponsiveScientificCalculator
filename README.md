# ResponsiveScientificCalculator
A Responsive scientific calculator


You can find the calculator here:
https://valerioviale.github.io/ResponsiveScientificCalculator/


<img width="948" alt="Screenshot 2024-03-01 at 14 13 59" src="https://github.com/valerioviale/ResponsiveScientificCalculator/assets/34212301/4afa2e3c-6f2a-42f3-9b36-135446334425">



This is a JavaScript code for a basic calculator application. The calculator has various buttons for arithmetic operations, special functions, and other operations.

The calculator screen has two sections, the main section (Screen1) and a secondary section (Screen2), which are both accessed via the getElementById method. The Brand is an element in the HTML with a class of Brand. The innerHTML method is used to set its content to an empty string.

The various buttons on the calculator are also accessed using the getElementById method and stored in variables. These include buttons for the numbers 0-9, the decimal point, arithmetic operators (addition, subtraction, multiplication, division), special functions (trigonometric functions, logarithmic functions, factorial, nPr, and nCr), and other operations (backspace, clear, clear all, equal, percent, etc.).

Functions for calculating factorials, permutations, and combinations are also defined.

Event listeners are added to the numeric and operator buttons, so that when clicked, their corresponding value is added to the main section screen (Screen1), and the corresponding expression is added to the Expression variable.

Other event listeners are added for the special functions, clear, clear all, backspace, and equal buttons. When the clear button is clicked, the expression and main screen are cleared. The clear all button is used to reset the calculator. The backspace button deletes the last entered value in the main screen. The equal button evaluates the expression stored in the Expression variable and displays the result on the main screen.

Overall, this code creates a simple calculator that can perform basic arithmetic operations, special functions, and other mathematical operations.
