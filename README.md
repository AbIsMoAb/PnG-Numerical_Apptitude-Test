# PnG-Numerical_Apptitude-Test
This is a code made for practicing the numerical puzzle part of P&amp;G apptitude test
The game represents a simple arithmetic equation with multiple variables and the final result
e.g ( _ x _ +_ = 50)
the goal is to guess the correct numbers that solve the equation, and try to solve as many problems as possible in the time given

## Description:
Like the test itself the code only allow for: 
- operations: subtraction, addition, division and multiplication.
- numbers between: 1 and 9 
- a number may be used only once
- The minimum number of variables is two and maximum number is 5
- Only natural numbers are allowed for the final result

## Logic:
The code follows a simple top down logical approach:
- A random number (n)of Variables are generated.
- A random set of mathematical operators are generated with lenght = (n-1)
- The result of these operations is then obtained. 
- The user is presented with the final result and the mathematical representation e.g ( _ + _ / _ = 15)
- The user has to enter the numbers (guesses) in order
- The result of the numbers given by the users is plugged in the equation and compared to the previously obtained result.
- The game continues until the user quits.

## Improvement points:
- Keeping score.
- Adding time limit to induce the user to solve faster.
- Increasing difficulity as user progresses instead of current random difficulity.
