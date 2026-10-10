# Monte Carlo Method for sin(x)

A simple C program that applies the Monte Carlo method to the `sin(x)` function.

The program generates random points, evaluates them using the sine function, and saves the input, output, and `sin(x)` data to a text file.

## Requirements

- A C compiler such as GCC
- The C standard math library

## Compilation

Compile the program with GCC:

```bash
gcc main.c -o monte_carlo -lm
```

> Replace `main.c` with the actual source file name if it is different.

The `-lm` option links the C math library, which is required for functions such as `sin()`.

## Usage

Run the compiled program:

### Linux and macOS

```bash
./monte_carlo
```

### Windows

```powershell
.\monte_carlo.exe
```

The generated input, output, and sine values can be viewed in the text file created by the program.

## Purpose

This project was created to practise:

- The Monte Carlo method
- Random number generation in C
- Mathematical functions
- File input and output
- Basic numerical programming

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

Created by [Emrullah Yarar](https://github.com/EmrullahYarar).
