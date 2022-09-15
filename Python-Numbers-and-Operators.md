# Python Number and Operators.

## Overview
In python programminng numbers and operators are part fo the building blocks when you arwe tryig to learn and understand this awesome language.
To program well, you don't have to be an expert in math. In the real sense, most programmers only require a basic understanding of algebra Numbers are an essential component of every programming language, and Python is no different.

In this article, let me highlight what we will cover.
- Integers and Floats
	- Integers 
	- Floating-Point Numbers
	- Complex Numbers

- Operators
	- Subtraction
	- Addition
	- Multiplication
	- Division
	- Integer Division
	- Exponents
	- The Modulus Operator
	- Arithmetic Expressions

- Math Functions and Number Methods
	- The pow() function
	- The abs() function
	- The round() function

 Let's jump right straight to it.

## Integers
A whole number without any decimal places is called an integer. Like, 2.0 is not an integer, but 2 is. You can use the `type()` function to determinte its data type, which is int.

```python
type(2)

#<class 'int'>
```
You can also declare a varialbe and assign it to an integer and check its data type.

```python
x = 10
type(x)

#<class 'int'>
```
> **Note**: You can change the data type of an integer to a string by adding two quotes, y = "2" and if you check: type(y) you will get string.

## Float number
Floats of floating-point number is a number wirh decimal place. Example: 25.90, 2.6, -0.8, etc you can determine its data type with the `type()` funstion. 

```python
type(2.6)
type(2.6)
type(-0.8)

#<class 'float'>
```
You can also convert a string to a float by using the `float()` method:
```python
float("2.5")

# 2.5
```
In python **E notation** is used to display large floating-point numbers:
```python
200000000000000000.0

# 2e+17
```
Finally for the floats section, when you have reached the maximum floating-point number in python, it returns a special float value called `inf`, where `inf` is called **infinity**.
```python
3e500

#inf
```
## Compelx number
One of the few programming languages with built-in complex number support is Python. In Python, you just write the real component, a plus sign, and then the imaginary part with the letter `j` at the end to make a complex number.

```python
x = 3 + 5j
print(x) #(3+5j)
```
Imaginary numbers have two attributes `.real` & `.imag`, when called it returns the number's real and imaginary components, respectively.
```python
x.real   #3.0
x.imag   #5.0
```
Python returns both the real and imaginary components as floats.

## Subtraction
You can perform subtraction operation you just have to put a dash or the minus sign  `-` between them.

```python
5 - 2 #3
5.0 - 2 #3.0
```
Whenevr you sepearate each operand with parentheses you will get a positive value.
```python
6 - (-4) #10
```

## Addition
You can perform addition operation with the `+` operator.

```python
5 + 2    #7
5.0 + 2  #7.0
```
## Multiplication
To multiply two numbers in python, you use the `*` operator.

```python
5 * 2    #10
5.0 * 2  #10.0
```

## Division
Use the `/` operator to divide two numbers in python.

```python
4 / 2   #2
7 / 2   #3.5
```

## Integer Division
Integer division is python is done using `//` and it is also known ad the floor division operator. In order to round down to an integer, the // operator first divides the number on the left by the number on the right.

```python
10 // 2    #5
5.0 // 2   #2.0
```

## Exponents
The ** operator can be used to increase a number to a power, also all exponents don't have to be an integer as it can also be a float.

```python
2 ** 3   #8
2 ** 4   #16
9 ** 0.5 #3.0
```
## The Modulus Operator
The remainder obtained by dividing the left operand by the right operand is what the modulus (or % operator) returns.

```python
7 % 3    #1
20 % 5   #0
```
`3` divides `7` twice and the remainder is `1`, so `7 % 3` is `1`.

## Arithmetic Expressions
Operators can be combined to create complex expressions. A grouping of integers, operators, and parentheses that Python can compute or evaluate to return a value is known as an expression. Expression evaluation follows the same guidelines as regular arithmetic. You most likely learnt these guidelines in school under the heading of **"order of operations"**.

```python
6*2 - 4      #8
10/5 + 2**2  #6
```

## Math Functions and Number Methods
Three of the most popular number methods that are built-in into Python will be discussed in this section.

**The round() function**:
To round a number to the nearest integer, use the `round()` function. 

```python
round(3.3)    #3
round(5.8)    #6
```
By giving a second parameter to `round()`, a number can be rounded to a specified number of decimal places.

```python
round(2.14459, 2)  #2.14
round(1.71887, 2)  #1.72
```

**The abs() function**:
The function `abs()` always yields a positive number of the same type as its input. That is, an integer's absolute value is always a positive integer, and a float's absolute value is always a positive float.

```python
abs(4)       #4
abs(-8.0)    #8.0
```
**The pow() function**:
We've spoken about using the `**` operator to raise a number to a power. `Pow()` can be used to accomplish the same goal. `Pow()` requires two arguments, the base, or the number to be raised to a power(it's the first argument), and the exponent, or the power to which the number is to be increased (it's the second argument).

```python
pow(3, 2)   #9
```
## Conclusion
In this article, we talked at length about the python number and operator, where we discussed about integers and floats. We touched complex numbers briefly in python. You got to know all the basic operators in python (subtraction, addition, multiplication, division, integer division, exponents, modulus Operator and ther arithmetic expressions). WE closed off by talking about the math functions and methods.

I hope you have really leanrt alot in this tutorial and this has really helped you understand python number and operators better.
Thanks for reading.


