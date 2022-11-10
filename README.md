# Lego--interpreter
Basic programming language interpreter.


## What is this program for?
It is used to calculate simple arithmetic expressions, can declare variables that hold a value in numbers or strings enclosed in double quotes and print them.

## Why Lego?
Building an interpreter, after reading [Raku](https://docs.raku.org/) documentation, I treated it as building something out of Lego blocks.

## The structure of the language:
A program is a sequence of instructions. Each statement is either a declaration, an assignment, or a print statement (printing the value of an expression). Expressions consist of numbers or variable names with the usual arithmetic operators ('+', '-', '*', '/') and parentheses, following the classic order of operations with exponentiation ('**'). Expressions can also accept strings enclosed in double quotes ("Hello World"). 

## Lego rules:
- The statement ends with -> ' .; '
- Variable declaration -> do x.;
- Value assignment -> '='
- Function call -> 'write(variable-name).;
- You can immediately assign a value to the declared variable


## How it's working ?
- Download the content of the repository: [Lego](https://github.com/Tomasz1577/interpreter.git)
![alt text](file:///C:/Users/tomas/OneDrive/Pulpit/image.jpg)
- If you don't have Raku, you need to download it: [Raku:download](https://www.raku.org/downloads)
- Then in the command line after entering the project folder:
```bash
raku .\interpreterLego .\t\test.lego
```

- The 't' folder contains tests related to grammar development.
