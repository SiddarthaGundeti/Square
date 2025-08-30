# Square

Input: 4

Output:

1111

2222

3333

4444

Question: Square
Write a program that reads a number N and prints a square of N rows and N columns using numbers starting from 1.

Example:

Approach:

Read the input number N.

Initialize a counter variable to keep track of the current row number.

Create a loop that runs N times.

In each iteration, print the current row number N times.

Step-by-Step Explanation:

Step 1: Read the input number

Read the input value representing the number N. We can use the input() function to read the input and int() to convert it into an integer.

Step 2: Initialize a counter variable

Initialize a counter variable called counter and set its value to 1. This variable will help us keep track of the current row number.

Step 3: Create a loop to print the square

Create a loop that runs N times. In each iteration, do the following:

Convert the current value of counter to a string.

Multiply the string by number to create a row with number repetitions of the current value of counter.

Print the row.

Increment the value of counter by 1.
