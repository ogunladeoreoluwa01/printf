<!-- @format -->

# Custom Print Formatter - \_printf Function

Welcome to the custom print formatter repository, which contains the source code for the versatile `_printf` function. This function is designed to provide flexible printing capabilities similar to the standard `printf` function, with added features.

## Introduction

The `_printf` function is capable of handling various data types and format specifiers. It can print characters, integers, strings, floats, hexadecimal values, and more. This project aims to create a function that offers the flexibility of the `printf` function while adhering to a similar format specifier syntax.

## Features

Our `_printf` function supports the following format specifiers:

- `%c`: Prints a character.
- `%d`: Prints an integer.
- `%s`: Prints a string.
- `%f`: Prints a float.
- `%x`: Prints a hexadecimal value.

## Syntax

```c
int _printf(const char *format, ...);
```

# The `_printf` function is variadic, allowing it to accept a variable number of arguments.
