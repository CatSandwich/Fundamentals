# Basics

## Statements & Expressions

Code is structured in the format of statements and expressions. 

### Expressions

An expression is a piece of code that holds a value.

Expressions "evaluate" to a value, which can then be used as that value. For example, `10 + 2` can be used anywhere that `12` can.

### Statements

A statement is a piece of code that *does not* hold a value. We will see some examples below. Expressions can often be used as a statement. Each statement is generally separated by a semicolon.

## Table of important statements and expressions

| Name | Type | Purpose | Syntax | Example(s) |
|------|------|---------|--------|------------|
| Literal | Expression | Allows a value to be used as an expression. | Varies | `10`, `"hello"`, `'c'` |
| Arithmetic | Expression | Allows for standard math arithmetic. | Varies | `2 + 2`, `5 / 3`, `3 * 4` |
| Variable declaration | Statement | Declares variables to be used later. | `[type] [name]` | `int num`, `std::string name` |
| Variable usage | Expression | Uses a previously defined variable. Evaluates to the value held by the variable. | `[variable name]` | `num`, `name` |
| Function declaration | Statement | Declares functions to be used later. | <pre>[return type] [name] ([parameters]) <br/>{<br/>    [function body]<br/>}</pre> | <pre>int add (int i1, int i2) <br/>{<br/>    return i1 + i2;<br/>}</pre> |
| Function call | Depends on return type | Runs a function. Evaluates to the returned value if non-void. | `[function name]([arguments])` | `add(10, 20)` |
