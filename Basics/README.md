# Basics

## Statements & Expressions

Code is structured in the format of statements and expressions. 

### Expressions

An expression is a piece of code that holds a value. Some examples:
- `10`
- `"hello!"`
- `(10 + 2) / 18`

Expressions "evaluate" to a value, which can then be used as that value. For example, `10 + 2` as an expression can be used anywhere that `12` can.

### Statements

A statement is a piece of code that *does not* hold a value. We will see some examples below. Expressions can often be used as a statement. Each statement is generally separated by a semicolon.

## Table of important statements and expressions

| Name | Type | Purpose | Syntax | Example(s) |
|------|------|---------|--------|------------|
| Literal | Expression | Allows a value to be used as an expression | Varies | `10`, `"hello"`, `'c'` |
| Arithmetic | Expression | Allows for standard math arithmetic | Varies | `2 + 2`, `5 / 3`, `3 * 4` |
| Variable declaration | Statement | Declares variables to be used later | `[type] [name]` | `int num`, `std::string name` |
| Function declaration | Statement | Declares functions to be used later | <pre>[return type] [name] ([parameters]) <br/>{<br/>    [function body]<br/>}</pre> | 
