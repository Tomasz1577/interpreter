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


![image](https://user-images.githubusercontent.com/95379724/201209460-72a69476-5d62-429f-a474-288d7c2569da.jpg)


- If you don't have Raku, you need to download it: [Raku:download](https://www.raku.org/downloads)

![raku](https://user-images.githubusercontent.com/95379724/201209819-2c709cda-b6aa-4e5e-b549-0ca4b2986f16.jpg)



- Then in the command line after entering the project folder:
```bash
raku .\interpreterLego .\t\test.lego
```

![testlego](https://user-images.githubusercontent.com/95379724/201210125-4dbb894a-8732-4245-bf31-26407cb31b05.jpg)


- The 't' folder contains tests related to grammar development.

## Summary:
The task was to create a 'simple' programming language interpreter (inspiration from other languages). It was an interesting challenge which allowed me to learn about many possibilities of Raku. Lego is the basic version of the interpreter that performs simple tasks. In the future, this project could be expanded with other functionalities.
