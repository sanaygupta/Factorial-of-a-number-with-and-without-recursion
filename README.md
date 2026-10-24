# Factorial-of-a-number-with-and-without-recursion

Factorial Using Recursion and Iteration in C  
Overview

This assignment focuses on calculating the factorial of a given non-negative integer using two approaches: iteration and recursion. The program demonstrates how user-defined functions can divide a problem into smaller, manageable tasks and return results to the calling function.

The main objective is to understand functions in C and explore the working of recursive functions compared with iterative solutions.

Objectives
Understand the definition and purpose of user-defined functions.
Learn the syntax and implementation of functions in C.
Understand the use of the return statement.
Differentiate between formal and actual arguments.
Learn how recursion works through repeated function calls.
Compare recursive and iterative approaches to solving a problem.
Problem Description

The factorial of a non-negative integer n, represented as n!, is the product of all positive integers from 1 to n.

Mathematically:

n! = n × (n - 1) × ... × 2 × 1, for n > 0
0! = 1

For example:

5! = 5 × 4 × 3 × 2 × 1 = 120

The program computes this value using both a loop and a recursive function.

Concepts Covered
User-Defined Functions: Functions created by the programmer to perform specific tasks.
Function Declaration and Definition: Specifying a function's interface and implementing its logic.
Function Calls: Invoking a function to execute its code.
Return Statement: Returning a computed value to the calling function.
Actual Arguments: Values or expressions passed to a function during a call.
Formal Arguments: Parameters that receive values within the function definition.
Recursion: A technique in which a function calls itself until a base condition is reached.
Iteration: Repeating instructions using a loop such as for or while.
Algorithm
Iterative Approach
Start the program.
Read a non-negative integer n.
Initialize the factorial variable to 1.
Multiply the factorial variable by each integer from 1 to n.
Display the calculated factorial.
Stop the program.
Recursive Approach
Start the program.
Read a non-negative integer n.
Call the recursive factorial function.
If n is 0 or 1, return 1 (base case).
Otherwise, return n * factorial(n - 1).
Display the calculated factorial.
Stop the program.
Sample Output
Enter a number: 5

Factorial using iteration = 120
Factorial using recursion = 120

Iteration vs. Recursion
Feature	    Iteration	            Recursion
Approach	   Uses loops	        Uses repeated function calls
Termination	 Loop condition     Base Case
Memory usage Usually lower	    Uses additional call-stack memory
Readability	 Often straight     Closely follows the mathematical definition
forward for factorial	


Learning Outcomes

By completing this assignment, I learned how to define and call user-defined functions, pass arguments, return values, and solve problems using recursion. I also understood the differences between iterative and recursive techniques.

Conclusion

This assignment demonstrates the calculation of factorials using both iterative and recursive functions in C. It provides practical experience with functions, return statements, recursion, and problem-solving techniques.

Technologies Used

Language: C

Platform: 64-bit Linux

Editor: gedit or any C-compatible code editor
