
# Python -Cheatsheet for Developers

## Introduction-What-is-Python?

> Python is a high-level, interpreted, general-purpose programming language renowned for its simplicity, readability, and extensive libraries. Its clear and concise syntax, often resembling natural language, makes it easy for beginners to learn while being powerful enough for experienced developers. Python's versatility allows it to be used in a vast array of applications, from web development (Django, Flask) and data science (NumPy, Pandas, Scikit-learn) to artificial intelligence, machine learning, automation, scripting, and scientific computing. Its large and active community contributes to a rich ecosystem of modules and frameworks, further expanding its capabilities and making it a highly productive choice for diverse programming tasks.


## 1. Basic Syntax & Comments

> This section covers the fundamental rules for writing Python code and how to add explanatory notes within your scripts.

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

> Learn how to declare variables and understand the various types of data Python handles, such as numbers, text, and booleans.

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

> Discover the symbols and keywords used to perform operations on values and variables, including arithmetic, comparison, and logical operations.

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

> Understand how to direct the execution of your code based on conditions (if/else) and how to repeat actions (for, while loops).

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

> This section explains how to define reusable blocks of code that perform specific tasks, improving code organization and efficiency.

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

## 6. Common Built-in Data Structures

> Explore Python's fundamental ways to organize and store collections of data, including lists, tuples, dictionaries, and sets.

|Command | description|
|----------|-------------|
|`my_list = []`|	Creates an empty list (mutable, ordered collection).|
|`my_list = [1, 'a', 3.14]`|	Creates a list with initial elements.|
|`my_list.append(item)`|	Adds item to the end of the list.|
|`my_list.extend(iterable)`|	Extends the list by appending elements from an iterable.|
|`my_list.insert(index, item)`|	Inserts item at a specific index.|
|`my_list.remove(item)`|	Removes the first occurrence of item from the list.|
|`my_list.pop([index])`|	Removes and returns the item at index (default: last item).|
|`my_list.sort()`|	Sorts the list in-place.|
|`sorted(iterable)`|	Returns a new sorted list from the iterable without modifying the original.|
|`my_list.count(item)`|	Returns the number of times item appears in the list.|
|`my_list.index(item)`|	Returns the index of the first occurrence of item.|
|`my_tuple = ()`|	Creates an empty tuple (immutable, ordered collection).|
|`my_tuple = (1, 'a', 3.14)`|	Creates a tuple with initial elements.|
|`my_tuple = 1, 'a', 3.14`|	Tuples can be created without parentheses (tuple packing).|
|`my_dict = {}`|	Creates an empty dictionary (mutable, unordered collection of key-value pairs).|
|`my_dict = {'key1': 'value1', 'key2': 2}`|	Creates a dictionary with initial key-value pairs.|
|`my_dict['key'] = value`|	Adds or updates a key-value pair in the dictionary.|
|`my_dict.get('key', default_value)`|	Returns the value for key if it exists, otherwise default_value.|
|`my_dict.keys()`|	Returns a view object of all keys in the dictionary.|
|`my_dict.values()`|	Returns a view object of all values in the dictionary.|
|`my_dict.items()`|	Returns a view object of all key-value pairs (as tuples) in the dictionary.|
|`my_dict.pop('key')`|	Removes key and returns its value.|
|`my_dict.update(other_dict)`|	Merges other_dict's key-value pairs into my_dict.|
|`my_set = set()`|	Creates an empty set (mutable, unordered collection of unique elements).|
|`my_set = {1, 2, 3}`|	Creates a set with initial elements.|
|`my_set.add(item)`|	Adds an item to the set.|
|`my_set.remove(item)`|	Removes item from the set; raises KeyError if not found.|
|`my_set.discard(item)`|	Removes item from the set if present, otherwise does nothing.|
|`my_set.union(other_set)`|	Returns a new set with all unique elements from both sets.|
|`my_set.intersection(other_set)`|	Returns a new set with common elements between both sets.|
|`my_set.difference(other_set)`|	Returns a new set with elements in my_set but not in other_set.|
|`my_set.issubset(other_set)`|	Returns True if my_set contains all elements of other_set.|
|`my_set.issuperset(other_set)`|	Returns True if other_set contains all elements of my_set.|

## 7. String Manipulation

> Master techniques for creating, accessing, modifying, and formatting text data within your programs.

|Command | description|
|----------|-------------|
|`'hello' + ' world'`|	Concatenates (joins) two or more strings.|
|`'abc' * 3`|	Repeats a string a specified number of times.|
|`len('string')`|	Returns the number of characters in a string.|
|`'Python'[0]`|	Accesses a character at a specific index (0-based) in a string.|
|`'Python'[1:4]`|	Slices a substring from a start index (inclusive) to an end index (exclusive).|
|`'Python'[-1]`|	Accesses a character from the end of the string (e.g., -1 is the last character).|
|`'hello'.upper()`|	Converts all characters in the string to uppercase.|
|`'HELLO'.lower()`|	Converts all characters in the string to lowercase.|
|`'hello world'.capitalize()`|	Converts the first character of the string to uppercase and the rest to lowercase.|
|`'hello world'.title()`|	Converts the first character of each word to uppercase.|
|`' hello '.strip()`|	Removes leading and trailing whitespace characters.|
|`' hello '.lstrip()`|	Removes leading whitespace characters.|
|`' hello '.rstrip()`|	Removes trailing whitespace characters.|
|`'Python'.replace('o', '0')`|	Replaces all occurrences of a specified substring with another substring.|
|`'one,two,three'.split(',')`|	Splits a string into a list of substrings using a specified delimiter.|
|`','.join(['one', 'two'])`|	Joins elements of an iterable (e.g., a list of strings) into a single string using the string as a separator.|
|`'word'.startswith('w')`|	Returns True if the string starts with the specified prefix.|
|`'word'.endswith('d')`|	Returns True if the string ends with the specified suffix.|
|`'abc'.find('b')`|	Returns the lowest index where the substring is found, or -1 if not found.|
|`'abc'.count('a')`|	Returns the number of times a substring appears in the string.|
|`'123'.isdigit()`|	Returns True if all characters in the string are digits.|
|`'abc'.isalpha()`|	Returns True if all characters in the string are alphabetic and not empty.|
|`'abc'.isalnum()`|	Returns True if all characters are alphanumeric (letters or numbers).|
|`'abc'.islower()`|	Returns True if all cased characters are lowercase.|
|`'ABC'.isupper()`|	Returns True if all cased characters are uppercase.|
|`f"Value: {var}"`|	f-string (formatted string literal) for easy string formatting with variable embedding.|
|`'Value: {}'.format(var)`|	str.format() method for flexible string formatting.|
|`"%s is %d" % ("Age", 30)`|	Old-style % formatting (similar to C's printf).|

## 8. File Input/Output (I/O)

> Learn how to read from and write data to files, enabling your programs to interact with external storage.

|Command | description|
|----------|-------------|
|`open('filename.txt', 'mode')`|	Opens a file and returns a file object. mode can be 'r' (read), 'w' (write, truncates existing), 'a' (append), 'x' (create new, exclusive), 'b' (binary), 't' (text - default), '+' (read/write).|
|`with open('filename.txt', 'r') as file:`|	The recommended way to open files. Ensures the file is automatically closed even if errors occur.|
|`file.read()`|	Reads the entire content of the file as a single string.|
|`file.readline()`|	Reads one line from the file at a time, including the newline character.|
|`file.readlines()`|	Reads all lines from the file and returns them as a list of strings.|
|`file.write('some text')`|	Writes the specified string to the file. Returns the number of characters written.|
|`file.writelines(list_of_strings)`|	Writes a list of strings to the file. No newline characters are added automatically.|
|`file.close()`|	Closes the file. Crucial when not using with statement to release system resources.|
|`file.tell()`|	Returns the current position of the file pointer (in bytes).|
|`file.seek(offset, whence=0)`|	Changes the current file pointer position. whence=0 (start), 1 (current), 2 (end).|
|`os.remove('filename.txt')`|	Deletes a file from the file system. Requires importing the os module.|
|`os.rename('old_name.txt', 'new_name.txt')`|	Renames a file. Requires importing the os module.|
|`os.path.exists('path/to/file')`|	Checks if a file or directory exists at the specified path. Requires importing os.|
|`os.mkdir('new_directory')`|	Creates a new directory. Requires importing the os module.|
|`os.makedirs('path/to/new/dirs')`|	Creates directories recursively. Requires importing the os module.|
|`os.listdir('directory_path')`|	Returns a list of all files and directories within the specified path. Requires importing os.|
|`json.load(file_object)`|	Reads JSON data from a file object and converts it to a Python object (dictionary or list). Requires importing json.|
|`json.dump(obj, file_object)`|	Writes a Python object (obj) to a file in JSON format. Requires importing json.|
|`csv.reader(file_object)`|	Returns a reader object that iterates over lines in the CSV file. Requires importing csv.|
|`csv.writer(file_object)`|	Returns a writer object for writing data to the CSV file. Requires importing csv.|
|`pd.read_csv('data.csv')`|	(Pandas) Reads data from a CSV file directly into a DataFrame.|
|`df.to_csv('output.csv', index=False)`|	(Pandas) Writes DataFrame to a CSV file. index=False prevents writing the DataFrame index.|

## 9. Error Handling

> Understand how to anticipate and gracefully manage errors and exceptions that may occur during program execution.

|Command | description|
|----------|-------------|
|`try:`|	Marks a block of code where exceptions might occur.|
|`except ExceptionType:`|	Catches a specific type of exception (e.g., ValueError, TypeError). Code inside this block runs if the specified exception occurs in the try block.|
|`except (ExceptionType1, ExceptionType2):`|	Catches multiple specific types of exceptions.|
|`except Exception as e:`|	Catches an exception and assigns the exception object to the variable e for further inspection.|
|`except:`|	Catches any type of exception (broad exception handling; generally discouraged as it can hide bugs).|
|`else:`|	Code in this block is executed if the try block completes without raising an exception.|
|`finally:`|	Code in this block is always executed, regardless of whether an exception occurred or not (useful for cleanup).|
|`raise ExceptionType("Error message")`|	Explicitly raises a specific exception with a custom error message.|
|`assert condition, "Error message"`|	Checks if a condition is true. If false, it raises an AssertionError with the optional message.|
|`sys.exc_info()`|	Returns a tuple containing information about the current exception being handled: (type, value, traceback). (Requires import sys)|
|`traceback.print_exc()`|	Prints the full traceback of the most recent exception. (Requires import traceback)|

## 10. Object-Oriented Programming (OOP)

> Delve into the principles of organizing code using objects and classes, promoting modularity and reusability.


|Command | description|
|----------|-------------|
|`class MyClass:`| Defines a new class named MyClass.|
|`def __init__(self, arg1, ...):`|	The constructor method, automatically called when a new object (instance) is created. self refers to the instance itself.|
|`self.attribute = value`|	Inside a method, self.attribute is used to define or access an instance variable (attribute) unique to each object.|
|`def my_method(self, arg1, ...):`|	Defines an instance method for the class. self is the first parameter.|
|`obj = MyClass(arg1_val, ...)`|	Creates a new instance (object) of MyClass.|
|`obj.attribute`|	Accesses an attribute of an object.|
|`obj.my_method()`|	Calls a method of an object.|
|`class ChildClass(ParentClass):`|	Defines ChildClass as a subclass of ParentClass, inheriting its attributes and methods.|
|`super().__init__(...)`|	Calls the constructor of the parent class from within the child class's constructor.|
|`def __str__(self):`|	Defines the "informal" string representation of an object, called by str() and print().|
|`def __repr__(self):`|	Defines the "official" string representation of an object, called by repr().|
|`@property`|	A decorator used above a method to turn it into a "getter" for an attribute, allowing access without ().|
|`@method.setter`|	A decorator used with a @property method to define a "setter" for that attribute.|
|`@classmethod`|	A decorator that turns a method into a class method, receiving the class itself (cls) as the first argument.|
|`@staticmethod`|	A decorator that turns a method into a static method; it doesn't receive self or cls implicitly.|
|`isinstance(obj, Class)`|	Checks if obj is an instance of Class or a subclass of Class.|
|`issubclass(SubClass, ParentClass)`|	Checks if SubClass is a subclass of ParentClass.|

## 11. Modules and Packages

> Learn how to organize your code into reusable files and directories, and how to import external libraries to extend functionality.

|Command | description|
|----------|-------------|
|`import module_name`|	Imports the entire module_name, making its contents accessible via module_name.function() or module_name.variable.|
|`import module_name as mn`|	Imports module_name and assigns it the alias mn, allowing access via mn.function(). Useful for shorter names.|
|`from module_name import function_name`|	Imports only function_name directly from module_name, allowing it to be used without the module_name. prefix.|
|`from module_name import function1, class2`|	Imports multiple specific items from a module.|
|`from module_name import *`|	Imports all public names (not starting with _) from module_name directly into the current namespace. Generally discouraged due to potential name clashes.|
|`import package_name.module_name`|	Imports a specific module_name located within a package_name.|
|`from package_name import module_name`|	Imports module_name from package_name directly.|
|`from package_name.module_name import function_name`|	Imports a specific function_name from a module_name within a package_name.|
|`__init__.py`|	An (often empty) file that marks a directory as a Python package. It's executed when the package is imported.|
|`__pycache__`|	A directory created by Python to store compiled bytecode files (.pyc) for faster loading of modules.|
|`pip install package_name`|	Command-line tool to install external Python packages from the Python Package Index (PyPI).|
|`pip uninstall package_name`|	Command-line tool to uninstall an installed Python package.|
|`pip freeze > requirements.txt`|	Saves a list of all currently installed Python packages and their versions to requirements.txt for reproducibility.|
|`pip install -r requirements.txt`|	Installs all packages listed in a requirements.txt file.|

## 12. Comprehensions (List, Dict, Set)

> Discover concise and efficient ways to create lists, dictionaries, and sets using a single line of code.

|Command | description|
|----------|-------------|
|`[expr for item in iterable]`|	List Comprehension (Basic): Creates a new list by applying an expression expr to each item in an iterable.|
|`[expr for item in iterable if condition]`|	List Comprehension (Conditional): Creates a new list by applying an expression expr to each item in an iterable, but only if condition is true.|
|`[expr if condition else other_expr for item in iterable]`|	List Comprehension (Conditional Expression): Creates a new list where expr is applied if condition is true, otherwise other_expr is applied, for each item.|
|`[(expr1, expr2) for item1 in iter1 for item2 in iter2]`|	List Comprehension (Nested Loops): Creates a list by iterating through multiple iterables (like nested for loops).|
|`{key_expr: value_expr for item in iterable}`|	Dictionary Comprehension (Basic): Creates a new dictionary where key_expr is the key and value_expr is the value for each item in an iterable.|
|`{key_expr: value_expr for item in iterable if condition}`|	Dictionary Comprehension (Conditional): Creates a new dictionary, including only key-value pairs where condition is true.|
|`{expr for item in iterable}`|	Set Comprehension (Basic): Creates a new set containing unique elements by applying an expression expr to each item in an iterable.|
|`{expr for item in iterable if condition}`|	Set Comprehension (Conditional): Creates a new set, including only elements where condition is true.|
|`(expr for item in iterable)`|	Generator Expression: Creates a generator object that yields values one by one, similar to list comprehension but uses less memory for large datasets.|
