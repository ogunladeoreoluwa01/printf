# printf
# Custom `printf` Project

## Introduction
The Custom `printf` Project is a group project aimed at creating a custom implementation of the `printf` function in C. The `printf` function in C is a powerful and widely used function that allows for formatted output. The standard `printf` function supports a wide range of conversion specifiers and formatting options. In this project, we will focus on creating a basic implementation to handle `%c`, `%s`, `%d`, and `%i` conversion specifiers.

## Table of Contents
- [Concepts](#concepts)
- [Background Context](#background-context)
- [Resources](#resources)
- [Requirements](#requirements)
- [Supported Conversion Specifiers](#supported-conversion-specifiers)
- [How To Use](#how-to-use)
- [Examples](#examples)
- [Contributors](#contributors)
- [License](#license)

## Concepts
To successfully complete this project, it's essential to understand and apply the following concepts:
- Group Projects
- Pair Programming
- Flowcharts
- Technical Writing

## Background Context
The `printf` function is a fundamental part of the C standard library, and its primary purpose is to produce formatted output. It takes a format string as input and generates output based on the format specified. The format string can include conversion specifiers, which are placeholders for various data types that need to be formatted.

## Resources
Before starting the project, it's recommended to read or watch the following resources to gain a better understanding of the `printf` function and the concepts required for this project:
- [Secrets of printf](#link-to-secretsofprintf)
- [Group Projects concept page](#link-to-groupprojectsconceptpage)
- [Flowcharts concept page](#link-to-flowchartsconceptpage)
- `man` pages: `printf(3)`

## Requirements
To successfully complete this project, the following requirements should be met:
- The implementation should be done in the C programming language.
- All code files will be compiled on Ubuntu 20.04 LTS using `gcc` with specific options.
- The code should adhere to the Betty style guidelines.
- The implementation should handle the conversion specifiers `%c`, `%s`, `%d`, and `%i`.
- The `_printf` function should return the number of characters printed (excluding the null byte used to end output to strings).
- Output should be written to `stdout`, the standard output stream.
- The project should have a `README.md` file with essential information about the project.

## Supported Conversion Specifiers
The custom `_printf` function will support the following conversion specifiers:
- `%c`: Character
- `%s`: String
- `%d`: Signed decimal integer
- `%i`: Signed decimal integer

## How To Use
1. Clone the project repository: `git clone <repository-url>`
2. Compile the code as mentioned in the [Requirements](#requirements) section.
3. Create a C file and include the `main.h` header file in it.
4. Implement your custom functionality using the `_printf` function.
5. Use the custom `_printf` function in your C file as needed.
6. Compile your C file along with the provided source files to test the functionality.

## Examples
Here are some examples of how the custom `_printf` function can be used:
```c
#include <stdio.h>
#include "main.h"

int main(void)
{
    _printf("Hello, %s!\n", "world");
    _printf("The value of pi is approximately %f\n", 3.14159);
    _printf("The character is: %c\n", 'A');
    _printf("The number is: %d\n", 42);
    return (0);
}
```
Output:
```
Hello, world!
The value of pi is approximately 3.141590
The character is: A
The number is: 42
```

## Contributors
This project is a collaborative effort by the following contributors:
- Julien Barbier (Co-founder & CEO)
- [Contributor 1 Name]
- [Contributor 2 Name]

## License
This project is licensed under the terms of the [MIT License](LICENSE).
