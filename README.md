# Loops
# App used: VS Code
# Theory
Loops in C++ are control flow structures that allow for the repeated execution of a block of code. They are automate repetitive tasks, iterating over objects and implementing algorithms efficiently.

Types of Loops
C++ has three primary loops:

For Loop:
Used when the number of iterations is known beforehand.
Syntax -
for (initialization; condition; increment/decrement) {
    // loop body
}

While Loop:
Used when the number of iterations is unknown, and the loop continues as long as a condition is true.
Syntax -
while (condition) {
    // loop body
}

Do-while loop:
Executes the loop body at least once, then checks the condition. Useful when the loop must run at least once, regardless of the initial condition.
Syntax -
do { // loop body } while (condition);

# Algorithms
# Inverse Right Triangle
Start

Input

Read the desired height of the triangle (n) from the user.
Initialization

Set a counter variable row to n.
Outer Loop:

Repeat while row is greater than or equal to 1.
Set a counter variable col to 1.
Inner Loop:

Repeat while col is less than or equal to row:
Print the desired character (e.g., '*' or col) depending on the desired pattern.
Increment col by 1.
Newline:

Print a newline character to move to the next row.
Decrement:

Decrement row by 1.
End

# Reverse PRN
Input:
Read an integer PRN from the user.

Initialization:
Create a variable num to store the extracted digit.

Reversing Loop:
While PRN is greater than 0:

Extract the last digit of PRN using num = PRN % 10.

Print the extracted digit num.

Remove the last digit from PRN using PRN = PRN / 10.

Output:
The reversed number is printed to the console.

# Conclusuon
From This experiment We have learned and understand the use the for Loops and While loops in the programs.
