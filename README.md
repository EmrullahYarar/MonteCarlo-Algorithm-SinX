Monte Carlo Method for sin(x)

A simple C program that applies the Monte Carlo method to the sin(x) function.

The program generates random points, evaluates them using the sine function, and saves the input, output, and sin(x) data to a text file.
Requirements

Compilation

Compile the program with GCC:

gcc main.c -o monte_carlo -lm

    Replace main.c with the actual source file name if it is different.

The -lm option links the C math library, which is required for functions such as sin().
Usage

Run the compiled program:
Linux and macOS

./monte_carlo

Windows

.\monte_carlo.exe

The generated input, output, and sine values can be viewed in the text file created by the program.
Purpose

This project was created to practise:

License

This project is licensed under the MIT License. See the LICENSE file for details.
Author
Created by Emrullah Yarar.
