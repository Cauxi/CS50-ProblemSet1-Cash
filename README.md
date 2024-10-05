<h1>pset1-cash<\h1>

NOTE: Copying this data and using it for your submission will breach the academic honesty policy of CS50. Please make sure you learn the material and solve the problem on your own. It's worth it!

This is my solution to the CS50 "Cash" problem set, implemented in C. You can find more details about the problem here: https://cs50.harvard.edu/x/2024/psets/1/cash/

Problem Overview
The task in this problem set is to write a program that calculates the minimum number of coins required to give a user change. The program takes a dollar amount as input and outputs the fewest number of coins (quarters, dimes, nickels, and pennies) required to make up that amount.

This problem set was completed as part of the CS50: Introduction to Computer Science course. Uploading my solution to GitHub is done in line with CS50's academic honesty policy. See this Reddit thread for further discussion.

Program Structure
The main tasks in this program include:

Input Validation: Ensuring that the user provides a positive float number for the amount of change.
Coin Calculation: Breaking down the input into the fewest number of coins by repeatedly subtracting the largest coin denominations possible.
Output: Displaying the total number of coins used to make the change.
Key Steps:
Prompt for input: The program prompts the user to enter the amount of change owed.
Convert to cents: The input (in dollars) is converted into cents to avoid floating-point precision issues.
Calculate coins: The program calculates the fewest coins needed, prioritizing larger denominations (quarters, dimes, nickels, pennies).
Print result: Outputs the total number of coins required.
Note: The repository does not contain any files that were part of CS50’s provided libraries or sample inputs, such as the standard libraries or Makefile, which is used for compilation.

