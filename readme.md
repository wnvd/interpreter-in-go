# The Monkey Programming Language And Interpreter
This project is created following the ['Writing an Interpreter in Go'](https://interpreterbook.com/) Book By Thorstan Ball.

In this project we create a programming language 'Monkey' and it's Interpreter with the following features:
- C-like Syntax
- varaible binding
- intergers and booleans
- arithmetic expression
- built-in functions
- first-class and higher-order function
- closures
- a string data structure
- an array data structure
- a hash data structure

The Interpreter has the following major parts:
- the lexer
- the parser
- the Abstract Syntax tree (AST)
- the internal object system
- the evaluator

# Installation
you need go 1.20
```
git clone
cd
go run main.go
```

# Syntax
- Varaibles
```
let age = 1;
let name = "Monkey";
let result = 10 * (2 + 3);
```
- Arrays
```
let arr = [1, 2, 3, 4];
```
- Hashes
```
let employee = {"name": "Naveed", "age": 25};
```
- Built-in functions
    - puts 
    ```
    puts("hello world"); // hello world
    puts(123); // 123
    ```
    - len 
    ```
    len("four") // 4
    let arr = [1,2,3];
    len(arr); // 3
    ```
    - first, last, push, rest
    ```
    let arr = [1, 2, 3, 4];
    first(arr); // 1
    last(arr); // 4
    push(arr, 5); // [1, 2, 3, 4, 5]
    rest(arr); // [2, 3, 4, 5]
    ```
