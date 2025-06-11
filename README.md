# Python-Masterclass

# Numpy-Cheatsheet for Developers

## Introduction-What-is-Numpy?

> NumPy (Numerical Python) is the fundamental library for numerical computing in Python


## 1. Basic Syntax & Comments

> This section covers the standard way to bring the NumPy library into your Python scripts.

|Command | description|
|----------|-------------|
|`# This is a comment`|	Single-line comment: Text after # on a line is ignored by the interpreter.|
|`"""Multi-line comment"""`|	Multi-line string literals (triple quotes) are often used as multi-line comments or docstrings.|
|`print('Hello, World!')`|	Outputs text or variable values to the console.|
|`variable = value`|	Assigns a value to a variable name.|
|`1 + 1`|	Basic arithmetic operation (addition). Other operators include - (subtraction), * (multiplication), / (division), ** (exponentiation), % (modulo), // (floor division).|
|`name = 'Alice'`|	Assigns a string value. Strings can use single or double quotes.|
|`number = 10`|	Assigns an integer value.|
|`decimal = 3.14`|	Assigns a floating-point value.|
|`is_true = True`|	Assigns a boolean value (True or False). Case-sensitive.|
|`if condition:`|	Starts a conditional block; code inside runs if condition is True. Requires indentation.|
|`for item in iterable:`|	Starts a loop that iterates over each item in an iterable (e.g., list, string). Requires indentation.|
|`def my_function():`|	Defines a new function. Requires indentation for its body.|
|`class MyClass:`|	Defines a new class for object-oriented programming. Requires indentation for its body.|
|`import module_name`|	Imports an entire module, making its contents available.|
|`from module_name import specific_item`|	Imports specific items (functions, classes, variables) from a module.|

## 2. Variables and Data Types

> This section covers the standard way to bring the NumPy library into your Python scripts.

|Command | description|
|----------|-------------|
|`x = 10`|	Assigns the integer value 10 to the variable x.|
|`name = "Alice"`|	Assigns the string value "Alice" to the variable name.|
|`price = 99.99`|	Assigns the float value 99.99 to the variable price.|
|`is_active = True`|	Assigns the boolean value True to the variable is_active.|
|`my_list = [1, 2, 'three']`|	Creates a list, an ordered, mutable collection of items.|
|`my_tuple = (10, 'hello', False)`|	Creates a tuple, an ordered, immutable collection of items.|
|`my_dict = {'key': 'value', 'num': 123}`|	Creates a dictionary, an unordered collection of key-value pairs.|
|`my_set = {1, 2, 3, 3}`|	Creates a set, an unordered collection of unique items.|
|`None`|	Represents the absence of a value or a null value.|
|`type(variable)`|	Returns the data type of the variable.|
|`int()`|	Converts a value to an integer.|
|`float()`|	Converts a value to a floating-point number.|
|`str()`|	Converts a value to a string.|
|`bool()`|	Converts a value to a boolean.|
|`list()`|	Converts an iterable to a list.|
|`tuple()`|	Converts an iterable to a tuple.|
|`dict()`|	Creates an empty dictionary or converts a sequence of key-value pairs to a dictionary.|
|`set()`|	Converts an iterable to a set.|
|`id(variable)`|	Returns the unique identity (memory address) of the variable.|
|`del variable_name`|	Deletes a variable, making it no longer accessible.|

## 3. Operators

> This section covers the standard way to bring the NumPy library into your Python scripts.

|Command | description|
|----------|-------------|
|`+`|	Addition: Adds two operands. Also used for string concatenation and list/tuple merging.|
|`-`|	Subtraction: Subtracts the second operand from the first.|
|`*`|	Multiplication: Multiplies two operands. Also used for string repetition and list/tuple repetition.|
|`/`|	Division: Divides the first operand by the second, always returning a float.|
|`//`|	Floor Division: Divides the first operand by the second and returns the floor (integer part) of the result.|
|`%`|	Modulus: Returns the remainder of the division.|
|`**`|	Exponentiation: Raises the first operand to the power of the second.|
|`=`|	Assignment: Assigns the value on the right to the variable on the left.|
|`+=`|	Add AND Assign: Adds the right operand to the left operand and assigns the result to the left operand (e.g., x += y is equivalent to x = x + y).|
|`-=`|	Subtract AND Assign: Subtracts the right operand from the left operand and assigns the result (e.g., x -= y is equivalent to x = x - y).|
|`*=`|	Multiply AND Assign: Multiplies the left operand by the right operand and assigns the result (e.g., x *= y is equivalent to x = x * y).|
|`/=`|	Divide AND Assign: Divides the left operand by the right operand and assigns the result (e.g., x /= y is equivalent to x = x / y).|
|`//=`|	Floor Divide AND Assign: Performs floor division and assigns the result (e.g., x //= y is equivalent to x = x // y).|
|`%=`|	Modulus AND Assign: Performs modulus operation and assigns the result (e.g., x %= y is equivalent to x = x % y).|
|`**=`|	Exponent AND Assign: Performs exponentiation and assigns the result (e.g., x **= y is equivalent to x = x ** y).|
|`==`|	Equal to: Returns True if operands are equal, False otherwise.|
|`!=`|	Not equal to: Returns True if operands are not equal, False otherwise.|
|`>`|	Greater than: Returns True if the left operand is greater than the right.|
|`<`|	Less than: Returns True if the left operand is less than the right.|
|`>=`|	Greater than or equal to: Returns True if the left operand is greater than or equal to the right.|
|`<=`|	Less than or equal to: Returns True if the left operand is less than or equal to the right.|
|`and`|	Logical AND: Returns True if both operands are true.|
|`or`|	Logical OR: Returns True if at least one operand is true.|
|`not`|	Logical NOT: Reverses the logical state of its operand (e.g., not True is False).|
|`is`|	Identity: Returns True if both operands refer to the same object in memory.|
|`is not`|	Identity (negated): Returns True if both operands do not refer to the same object.|
|`in`|	Membership: Returns True if a value is found in a sequence.|
|`not in`|	Membership (negated): Returns True if a value is not found in a sequence.|
|`&`|	Bitwise AND: Performs a bit-by-bit AND operation.|
|`^`|	Bitwise XOR: Performs a bit-by-bit XOR (exclusive OR) operation.|
|`~`|	Bitwise NOT: Inverts all bits.|
|`<<`|	Bitwise Left Shift: Shifts bits to the left.|
|`>>`|	Bitwise Right Shift: Shifts bits to the right.|

## 4. Control Flow (Conditionals & Loops)

> This section covers the standard way to bring the NumPy library into your Python scripts.

|Command | description|
|----------|-------------|
|`if condition:`|	Begins an if statement; the indented code block executes if condition is True.|
|`elif condition:`|	(Optional) Stands for "else if"; an alternative condition to check if the preceding if/elif conditions were False.|
|`else:`|	(Optional) The indented code block executes if all preceding if/elif conditions were False.|
|`for item in iterable:`|	Begins a for loop, iterating through each item in an iterable (e.g., list, tuple, string, range).|
|`while condition:`|	Begins a while loop; the indented code block executes repeatedly as long as condition remains True.|
|`break`|	Immediately terminates the current for or while loop, skipping any remaining code in the loop.|
|`continue`|	Skips the rest of the current iteration of a for or while loop and proceeds to the next iteration.|
|`pass`|	A null operation; does nothing. Used as a placeholder where a statement is syntactically required but you don't want any code to execute.|
|`range(stop)`|	Generates a sequence of numbers from 0 up to (but not including) stop.|
|`range(start, stop)`|	Generates a sequence of numbers from start up to (but not including) stop.|
|`range(start, stop, step)`|	Generates a sequence of numbers from start up to (but not including) stop, incrementing by step.|
|`enumerate(iterable)`|	Used in for loops to get both the index and value of items in an iterable.|
|`zip(iterable1, iterable2)`|	Used in for loops to iterate over multiple iterables simultaneously.|
|`for x in my_list if x > 5:`|	(Within list/dict/set comprehensions) Adds a conditional filter to control which items are processed.|


## 5. Functions

> This section covers the standard way to bring the NumPy library into your Python scripts.

|Command | description|
|----------|-------------|
|`def my_function():`|	Defines a simple function named my_function that takes no arguments.|
|`def greet(name):`|	Defines a function greet that takes one required argument, name.|
|`def add(a, b=0):`|	Defines a function add with a required argument a and an optional argument b with a default value of 0.|
|`def calculate(*args):`|	Defines a function that accepts an arbitrary number of positional arguments, which are collected into a tuple args.|
|`def configure(**kwargs):`|	Defines a function that accepts an arbitrary number of keyword arguments, which are collected into a dictionary kwargs.|
|`def example(arg1, *args, kw1, **kwargs):`|	Shows a function definition with positional, arbitrary positional, keyword-only, and arbitrary keyword arguments.|
|`return value`|	Exits the function and sends value back to the caller. If omitted, None is returned.|
|`return val1, val2`|	Returns multiple values as a tuple.|
|`lambda x, y: x + y`|	Creates a small, anonymous function (a lambda function) that takes arguments x and y and returns their sum.|
|`my_function()`|	Calls (executes) the my_function.|
|`greet('Alice')`|	Calls the greet function, passing 'Alice' as the name argument.|
|`add(5, 3)`|	Calls add with positional arguments.|
|`add(a=10, b=2)`|	Calls add with keyword arguments.|
|`add(10, b=2)`|	Calls add with a mix of positional and keyword arguments.|
|`global_var`|	Declares that a variable inside a function refers to a global variable, allowing modification.|
|`nonlocal_var`|	Declares that a variable inside a nested function refers to a variable in the nearest enclosing (non-global) scope, allowing modification.|
|`@decorator_name`|	Syntax for applying a decorator to a function definition, modifying its behavior.|
|`docstring`|	A string literal, typically enclosed in triple quotes ("""Docstring"""), used immediately after a function header to document its purpose, arguments, and return values. Accessible via function.__doc__ or help(function).|




