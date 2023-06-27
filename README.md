# printf Project

This is a group project for the 0x11. C - printf course in C programming. The goal of this project is to write our own `printf` function that produces output according to a given format.

## Team Members
- Yvonne Chemtai Chelule

## Project Details
- Start Date:
- End Date:
- Weight: 5

## Project Summary
The project involves implementing various conversion specifiers and handling different flags, length modifiers, and custom conversion specifiers in the `printf` function. The implemented function should write the formatted output to the standard output stream.

## Requirements
- Allowed editors: vi, vim, emacs
- Compilation on Ubuntu 20.04 LTS using gcc with the following options: `-Wall -Werror -Wextra -pedantic -std=gnu89`
- All files should end with a new line
- Code should follow the Betty style
- No global variables allowed
- Maximum of 5 functions per file
- Prototypes of all functions should be included in the `main.h` header file
- Header files should be include guarded
- Do not push any `main.c` files to the repository (provided main.c files will be used for compilation)
- Do not include the `_putchar` function (not provided)

## Repository Guidelines
- One project repository per group
- Other team members should not fork or clone the project repository
- Risk of scoring 0% if multiple repositories are found

## Tasks
1. **I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life**
    - Implement the `printf` function with support for conversion specifiers: `%c`, `%s`, and `%%`.

2. **Education is when you read the fine print. Experience is what you get if you don't**
    - Extend the `printf` function to handle conversion specifiers: `%d` and `%i`.

3. **With a face like mine, I do better in print**
    - Implement custom conversion specifier `%b` to convert an unsigned integer to binary.

4. **What one has not experienced, one will never understand in print**
    - Extend the `printf` function to handle conversion specifiers: `%u`, `%o`, `%x`, and `%X`.

5. **Nothing in fine print is ever good news**
    - Optimize the `printf` function by using a local buffer of 1024 characters to reduce the number of `write` calls.

6. **My weakness is wearing too much leopard print**
    - Implement custom conversion specifier `%S` to print strings with non-printable characters represented as `\x` followed by the ASCII code value in hexadecimal.

7. **How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print**
    - Handle flag characters `+`, `space`, and `#` for non-custom conversion specifiers.

8. **Sarcasm is lost in print**
    - Handle length modifiers `l` and `h` for conversion specifiers: `%d`, `%i`, `%u`, `%o`, `%x`, and `%X`.

9. **Print some money and give it to us for the rain forests**
    - Implement field width (minimum number of characters to be printed) for non-custom conversion specifiers.

10. **The big print gives and the small print takes away**
    - Implement precision (number of digits to be printed for numeric conversion specifiers) for non-custom conversion specifiers.

## Files and Folders
- `README.md`: Project README file
- `main.c`: Entry point for the `printf` function and test cases
- `holberton.h`: Header file containing function prototypes and necessary libraries
- `*.c`: Individual source code files for each task
