# Scientific Calculator in C

Welcome to the **Scientific Calculator** project built in the C programming language! This is a simple terminal-based calculator that performs both basic and advanced mathematical operations.

## Features

This calculator supports the following operations:

1. ➕ Addition  
2. ➖ Subtraction  
3. ✖️ Multiplication  
4. ➗ Division  
5. % Modulus  
6.  Power (Exponentiation)  
7.  Factorial  
8.  Square  
9.  Cube  
10.  Square Root  

##  How to Use

1. Compile the code using a C compiler like `gcc`:
   ```bash
   gcc calculator.c -o calculator -lm
## Run the executable:


./calculator
Follow the on-screen instructions to select and perform operations.

## Code Overview
The program uses a while loop and a switch statement to continuously accept user input and perform the selected operation until the user chooses to exit (Press 0).

Each operation is implemented as a separate function for modularity and readability.



📌 Note
Division results are shown as floating-point numbers.

Factorial is implemented using a loop and only works for non-negative integers.

math.h library is used for advanced functions like pow() and sqrt().

## Author
Md. Junayed Bin Karim

 CSE Student at Daffodil International University

 karim22205101667@diu.edu.bd


