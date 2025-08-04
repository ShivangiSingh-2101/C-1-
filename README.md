Aim:
To write a C++ program that prints Hello World and takes two numbers as input from the user and performs basic arithmetic operations — addition, subtraction, multiplication, and division — and displays the results.

Theory:
In programming, arithmetic operations are the foundation of numerical computation. This program demonstrates the use of input/output statements, variables, and arithmetic operators in C++.
1. Input/Output in C++:
cin: Used to take input from the user.
cout: Used to display output on the screen.
<< and >>: These are insertion and extraction operators respectively.
 2. Variables and Data Types:
Variables are named storage locations in memory.
In this program, float data type is used to store numbers that can contain decimal values.
The variables n and m are used to store the input values.
Variables sum, sub, div, and must store the respective operation results.
 3. Arithmetic Operators in C++:
Operator	Operation	Example
+	Addition	a + b
-	Subtraction	a - b
*	Multiplication	a * b
/	Division	a / b
These operators are used to perform calculations on the two input numbers.
 4. Handling Division:
Division must be handled carefully, especially when the denominator (m) is zero, as this can cause runtime errors or return infinity (inf) in floating-point operations.
A real-world version of this program would include a condition to avoid dividing by zero.
 5. Importance of the Program:
Such basic programs form the building blocks of more complex logic in applications like calculators, billing software, financial computations, and scientific calculations.
It also helps beginners understand the flow of control, syntax, and the logic behind user interaction in C++.

ALGORITHM:


- Start the program
- Display "Hello World"
- Declare variables: n, m for inputs; sum, sub, mul, div for results
- Display a message: “Enter first number”
- Read input and store in n
- Display a message: “Enter second number”
- Read input and store in m
- Perform and store results:
- sum = n + m
- sub = n - m
- mul = n * m
- div = n / m
- Display all the results using cout
