*This is pulled from my c-playground repo.
# TinyVM

A lightweight virtual machine written in C that simulates CPU functionality by interpreting and executing simple programs. This VM uses an accumulator register and supports a minimal instruction set.  

## Features
- Supports a basic instruction set:
  - `HALT`: Stop execution.
  - `LOAD`: Load a value into the accumulator.
  - `ADD`: Add a value to the accumulator.
  - `SUB`: Subtract a value from the accumulator.
  - `PRINT`: Display the current accumulator value.
- Programs are defined as arrays of opcode-operand pairs.
- Trace mode for debugging, which prints instructions and register state as the program runs.

## Build Instructions
Compile with GCC:  
```bash
gcc -Iinclude src/*.c -o tinyvm
```
