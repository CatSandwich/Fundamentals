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
| Variable declaration | Statement | Declares a variable to be used later. | `[type] [name]` | `int num`, `std::string name` |
| Variable usage | Expression | Uses a previously defined variable. Evaluates to the value held by the variable. | `[variable name]` | `num`, `name` |
| Function declaration | Statement | Declares a function to be used later. | <pre>[return type] [name] ([parameters]) <br/>{<br/>    [function body]<br/>}</pre> | <pre>int add (int i1, int i2) <br/>{<br/>    return i1 + i2;<br/>}</pre> |
| Function call | Depends on return type | Runs a function. Evaluates to the returned value if non-void. | `[function name]([arguments])` | `add(10, 20)` |

## Operators

Operators are symbols that combine or transform expressions in various ways. Operators fall into various categories.

### Assignment Operator

The assignment operator assigns a value to a variable. 

| Name | Symbol | Purpose | Example(s) |
|------|--------|---------|------------|
| Assignment | `=` | Assigns a value to a variable. | `i = 10` |

### Arithmetic Operators

Arithmetic operators are most commonly used as an operation between two numeric expressions.

| Name | Symbol | Purpose | Example(s) |
|------|--------|---------|------------|
| Addition | `+` | Adds two expressions together. | `10 + 2` => 12 |
| Subtraction | `-` | Subtracts an expression from another. | `10 - 2` => 8 |
| Multiplication | `*` | Multiplies two expressions together. | `10 * 2` => 20 |
| Division | `/` | Divides an expression by another. Note that integer division discards decimals. | `11 / 2` => 5, <br/>`11.0 / 2.0` => 5.5 |
| Modulo | `%` | Divides an expression by another and returns the remainder. Only works with integers. | `11 % 2` => 1 |

### Increment and Decrement Operators

Increment and Decrement operators are shorthand operators that increment or decrement a variable by 1. In the following table, treat `i` as an integer variable that starts each example with a value of 10.

| Name | Symbol | Purpose | Example(s) |
|------|--------|---------|------------|
| Prefix increment | `++` | Increments a variable then evaluates to the new value. | `++i` => 11, i is now 11 |
| Postfix increment | `++` | Increments a variable then evaluates to the old value. | `i++` => 10, i is now 11 |
| Prefix decrement | `--` | Decrements a variable then evaluates to the new value. | `--i` => 9, i is now 9 |
| Postfix decrement | `--` | Decrements a variable then evaluates to the old value. | `i--` => 10, i is now 9 |
