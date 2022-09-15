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
	- Round Numbers With round()
	- Find the Absolute Value With abs()
	- Raise to a Power With pow()
	- Check if a Float Is Integral

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
You can also convert a string to a float by using the float() method:
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

## Subtraction
You can perform subtraction operation you just have to put a dash or the minus sign ( - ) between them.

```python
5 - 2 #3
5.0 - 2 #3.0
```
Whenevr you sepearate each operand with parentheses you will get a positive value.
```python
6 - (-4) #10
```

## Addition
You can perform addition operation with the + operator.

```python
5 + 2    #7
5.0 + 2  #7.0
```
## Multiplication
To multiply two numbers in python, you use the * operator.

```python
5 * 2    #10
5.0 * 2  #10.0
```

## Division
Use the / operator to divide two numbers in python.

```python
4 / 2   #2
7 / 2   #3.5
```

## Integer Division
Integer division is python is done using (//) and it is also known ad the floor division operator. In order to round down to an integer, the // operator first divides the number on the left by the number on the right.

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

## Arithmetic Expressions

- Math Functions and Number Methods
 - Round Numbers With round()
 - Find the Absolute Value With abs()
 - Raise to a Power With pow()
 - Check if a Float Is Integral

