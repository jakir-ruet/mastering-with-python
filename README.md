## More About Me – [Take a Look!](http://www.mjakaria.me)

### Overview

Python is a high-level, general-purpose programming language. Its design philosophy emphasizes code readability with the use of significant indentation. Python is dynamically typed and garbage-collected. It supports multiple programming paradigms, including structured, object-oriented and functional programming.

## Environment Setup

```bash
python3 -m venv venv # Install virtual environment
source venv/bin/activate
```

```bash
pip3 install virtualenv
```

```bash
virtualenv venv
```

```bash
source venv/bin/activate
```

- - -

Keyword

Keywords are reserved words with a predefined meaning. These words cannot be used as a function name, variable name, class name, etc. They are written in lower case except for True, False, and None and are case-sensitive.

| Keyword  | Description                                                                                                     |
| -------- | --------------------------------------------------------------------------------------------------------------- |
| and      | a logical operator that returns true if both the operands are true or else returns false                        |
| as       | used to create an alias                                                                                         |
| assert   | used during debugging to check the correctness of code                                                          |
| break    | Control statement used to break from a loop                                                                     |
| class    | used to define a class                                                                                          |
| continue | control statement used to continue to the next iteration of a loop                                              |
| def      | used to define a function                                                                                       |
| del      | used to delete the reference to the object                                                                      |
| elif     | condition statement used for the else if condition                                                              |
| else     | conditional statement that is executed if the is condition is false                                             |
| except   | Used in exceptions                                                                                              |
| False    | boolean value                                                                                                   |
| finally  | used with exceptions to execute a block of code that will be executed no matter if there is an exception or not |
| for      | Used in for loop                                                                                                |
| from     | import specific parts of a module                                                                               |
| global   | Used to declare a global variable                                                                               |
| if       | a conditional statement that executes if the condition is true                                                  |
| import   | Used to import a module                                                                                         |
| in       | used to check if a value is present in a list, tuple, etc.                                                      |
| is       | used to check if the two variables are equal or not                                                             |
| lamda    | used to create an anonymous function                                                                            |
| None     | used to represent a null value                                                                                  |
| nonlocal | used to declare a non-local variable                                                                            |
| not      | a logical operator that returns true if the operand is false or else returns false                              |
| or       | a logical operator that returns true if any one of the operands is true or else returns false                   |
| pass     | a null statement that does not do anything                                                                      |
| raise    | Used to raise an exception                                                                                      |
| return   | used to exit a function and return a value                                                                      |
| True     | boolean value                                                                                                   |
| try      | used to make a try-except statement                                                                             |
| while    | used in while loop                                                                                              |
| with     | used to simplify exception handling                                                                             |
| yield    | used to end a function and return a generator                                                                   |

- - -

Identifier

An identifier is a user-defined name used to identify entities like class, functions, variables, etc. They are used to differentiate one entity from another.

Rules to name an identifier

While naming an identifier, a set of rules needs to be followed to have a valid identifier. The rules are:

1. An identifier can be a combination of digits, underscore, and letters in lowercase or uppercase.
2. Keywords are not allowed to be used as identifiers.
3. An identifier cannot have any spaces.
4. Digits cannot be used in the starting position of identifiers.
5. Special symbols like !, @, #, $, %, etc are not allowed.

- - -

Differences & Comparison between Keywords and Identifiers

| Keyword                                                             | Identifier                                                           |
| ------------------------------------------------------------------- | -------------------------------------------------------------------- |
| Keywords are the reserved words with a special meaning.             | Identifiers are the user-defined names of variables, functions, etc. |
| They are written in lower case except for True, False, and None.    | Need not be written in lowercase.                                    |
| It helps to identify a specific property that exists within Python. | It identifies the name of the particular entity.                     |
| Contains only letters                                               | Contains letters, underscore, and digits.                            |
| Example:- or, raise, pass                                           | Example:- maxCount, minNum1, etc                                     |

- - -

Statement

A statement is an instruction that a Python interpreter can execute. So, in simple words, we can say anything written in Python is a statement.

- - -

Indentation

Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important.

- - -

Comments

The hash (#) symbol to start writing a comment. Comments can be used to explain Python code. it can be used to make the code more readable. and can be used to prevent execution when testing code. it is single line & multi-line.

- - -

Variable & Scoping

Variables are containers for storing data values.

1. A variable name must start with a letter or the underscore character
2. A variable name cannot start with a number
3. A variable name can only contain alphanumeric characters and underscores (A-z, 0-9, and \_ )
4. Variable names are case-sensitive (age, Age and AGE are three different variables)

- - -

Literals

Literal is a raw data given in a variable or constant.

| Category                   | Literal Type  | Description                   | Example                          |
| -------------------------- | ------------- | ----------------------------- | -------------------------------- |
| **1. Numeric Literals**    | `int`         | Whole numbers (no decimal)    | `10`, `-5`, `1000`               |
|                            | `float`       | Decimal numbers               | `10.5`, `3.14`, `-0.9`           |
|                            | `complex`     | Real + imaginary part         | `3+5j`, `1j`, `2-4j`             |
| **2. String Literals**     | Single quotes | Text inside `' '`             | `'Hello'`                        |
|                            | Double quotes | Text inside `" "`             | `"Jakaria"`                      |
|                            | Triple quotes | Multi-line strings            | `"""Hello World"""`              |
| **3. Boolean Literals**    | `True`        | Represents logical true       | `is_valid = True`                |
|                            | `False`       | Represents logical false      | `is_paid = False`                |
| **4. Special Literal**     | `None`        | Represents "no value" / null  | `value = None`                   |
| **5. Collection Literals** | List literal  | Ordered, mutable collection   | `[1, 2, 3]`                      |
|                            | Tuple literal | Ordered, immutable collection | `(1, 2, 3)`                      |
|                            | Dict literal  | Key–value pairs               | `{"name": "Jakaria", "age": 30}` |
|                            | Set literal   | Unique unordered items        | `{1, 2, 3}`                      |

- - -

Data Types

The particular kind of data item, as defined by the values it can take, the programming language used, or the operations that can be performed for the purpose of real time use.

| Category           | Data Type    | Description                        | Example                          |
| ------------------ | ------------ | ---------------------------------- | -------------------------------- |
| **Text Type**      | `str`        | Immutable text sequence            | `"Jakaria"`                      |
| **Numeric Types**  | `int`        | Integer numbers                    | `25`                             |
|                    | `float`      | Decimal numbers                    | `10.5`                           |
|                    | `complex`    | Complex numbers (real + imaginary) | `3 + 5j`                         |
| **Sequence Types** | `list`       | Ordered, mutable sequence          | `[1, 2, 3]`                      |
|                    | `tuple`      | Ordered, immutable sequence        | `(10, 20)`                       |
|                    | `range`      | Sequence of numbers                | `range(1, 5)`                    |
| **Mapping Type**   | `dict`       | Key–value pairs                    | `{"name": "Jakaria", "age": 30}` |
| **Set Types**      | `set`        | Unordered, unique items, mutable   | `{1, 2, 3}`                      |
|                    | `frozenset`  | Unordered, unique items, immutable | `frozenset({1, 2, 3})`           |
| **Boolean Type**   | `bool`       | True or False                      | `True`                           |
| **Binary Types**   | `bytes`      | Immutable byte sequence (0–255)    | `bytes([65, 66])`                |
|                    | `bytearray`  | Mutable byte sequence (0–255)      | `bytearray([65, 66])`            |
|                    | `memoryview` | Memory view of binary data         | `memoryview(bytes(5))`           |
| **None Type**      | `NoneType`   | Represents null / no value         | `None`                           |

- - -

Comparison & Differences List, Tuple, Set, & Dictionary

| Feature                 | **List**                                | **Tuple**                     | **Set**                              | **Dictionary**                          |
| ----------------------- | --------------------------------------- | ----------------------------- | ------------------------------------ | --------------------------------------- |
| **Definition**          | Ordered collection of items             | Ordered, immutable collection | Unordered collection of unique items | Unordered collection of key–value pairs |
| **Mutable?**            | Yes                                     | No                            | Yes (items must be immutable)        | Yes                                     |
| **Duplicates allowed?** | Yes                                     | Yes                           | No                                   | Keys: No, Values: Yes                   |
| **Indexing / Slicing**  | Yes                                     | Yes                           | No                                   | Keys only (no numeric indexing)         |
| **Order (3.7+)**        | Maintains order                         | Maintains order               | No guaranteed order                  | Maintains insertion order               |
| **Syntax**              | `[1, 2, 3]`                             | `(1, 2, 3)`                   | `{1, 2, 3}`                          | `{'a': 1, 'b': 2}`                      |
| **Example**             | `nums = [1, 2, 2, 3]`                   | `nums = (1, 2, 3)`            | `nums = {1, 2, 3}`                   | `info = {'name': 'Jakaria', 'age': 30}` |
| **Use Case**            | When you need a modifiable ordered list | Fixed data, faster than list  | Unique items and set operations      | Fast key-based lookup                   |
| **Common Methods**      | `append(), pop(), sort()`               | `count(), index()`            | `add(), remove(), union()`           | `keys(), values(), items()`             |

- - -

Function

A function is a group of related statements designed to perform a specific task. There are two types of functions. A function is a reusable block of code that helps organize your program, making it more modular and reducing repetition. Functions can accept inputs, process them, and return outputs

Types

`Four` types function such as

| Function Type                | Description                             | Characteristics                                                                                         | Example                                                                                      |
| ---------------------------- | --------------------------------------- | ------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| **1. Built-in Function**     | Predefined functions provided by Python | • Already available<br>• No need to define<br>• Highly optimized                                        | `print("Hello")`<br>`len([1,2,3])`                                                           |
| **2. User-Defined Function** | Functions written by the programmer     | • Created using `def`<br>• Can take arguments<br>• Can return values                                    | `python\ndef greet(name):\n    return "Hello " + name`                                       |
| **3. Lambda Function**       | Small anonymous function with no name   | • Created using `lambda` keyword<br>• One-line function<br>• Often used with `map`, `filter`, `sorted`  | `square = lambda x: x*x`                                                                     |
| **4. Recursive Function**    | A function that calls itself            | • Must have a base condition<br>• Useful for repetitive tasks like factorial, Fibonacci, tree traversal | `python\ndef factorial(n):\n    if n == 1:\n        return 1\n    return n * factorial(n-1)` |

Higher Order Functions

Functions can also be passed as arguments to other functions, or they can return other functions. This is called higher-order functions.

Part

Four part in a function such as function

- Name,
- Parameter list,
- Body and
- Return statement

Terms **argument** and **parameter** are closely related, but they refer to **different** concepts. Understanding the distinction between them is essential for working with functions.

- **Parameter:** A parameter is a variable defined in the function definition. It acts as a placeholder for the value that will be passed to the function when it is called. Parameters are part of the function's signature and specify what kind of input the function expects.
- **Argument:** An argument is the actual value you pass to the function when you call it. It is the input provided to the function in place of the parameter. Arguments can be literals, variables, or even expressions.

```bash
def greet(name="Guest"):  # 'name' is a parameter with a default value
    print(f"Hello, {name}!")

greet()         # Output: Hello, Guest!  (No argument passed)
greet("Alice")  # Output: Hello, Alice!  (Argument passed)
```

#### From a function's perspective

- A parameter is the variable listed inside the parentheses in the function definition.
- An argument is the value that are sent to the function when it is called.

Key Difference

| **Parameter**                                                               | **Argument**                                                                            |
| --------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| A **parameter** is a variable in the function definition.                   | An **argument** is the actual value passed to the function when it is called.           |
| It acts as a placeholder for the value that will be passed to the function. | It is the input value provided to the function during the function call.                |
| Example: `def greet(name):` (`name` is a parameter)                         | Example: `greet("Alice")` ("Alice" is an argument)                                      |
| Parameters are defined in the function signature.                           | Arguments are passed during the function call.                                          |
| A function can have multiple parameters.                                    | A function can have multiple arguments corresponding to the parameters.                 |
| Parameters are used to specify what kind of input the function expects.     | Arguments are the actual values used to populate the parameters when the function runs. |

- - -

Recursion

Recursion is when a function calls itself until it reaches a base condition.

```bash
def factorial(n):
    if n == 0:
        return 1  # Base case
    return n * factorial(n - 1)  # Recursive call

print(factorial(5))  # Output: 120
```

Iteration

Iteration uses loops (`for` or `while`) to repeat a process.

```bash
def factorial_iter(n):
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result

print(factorial_iter(5))  # Output: 120
```

Recursion vs Iteration

| SL  | Recursion                                                   | Iteration                                         |
| --- | ----------------------------------------------------------- | ------------------------------------------------- |
| 1   | Terminates when the base case becomes true.                 | Terminates when the condition becomes false.      |
| 2   | Used with functions.                                        | Used with loops.                                  |
| 3   | Every recursive call needs extra space in the stack memory. | Every iteration does not require any extra space. |
| 4   | Smaller code size.                                          | Larger code size.                                 |

- - -

Lambda Function

A lambda function is a small anonymous function. It can take any number of arguments, but can only have one expression. syntax is lambda arguments: expression

1. Use: The power of lambda is better shown when you use them as an anonymous function inside another function.
2. Use: Say you have a function definition that takes one argument, and that argument will be multiplied with an unknown number:

- - -

Files

File handling is an important part of any web application. Python has several functions for creating, reading, updating, and deleting files.

1. `r` - Read Default value. Opens a file for reading, error if the file does not exist
2. `a` - Append Opens a file for appending, creates the file if it does not exist
3. `w` - Write Opens a file for writing, creates the file if it does not exist
4. `x` - Create: Creates the specified file, returns an error if the file exists
5. `t` - Text: Default value. Text mode
6. `b` - Binary: Binary mode (e.g. images)
7. "+" - Read-Write: Opens a file for updating (reading and writing)

- - -

Object & Class (OOP)

Class: A class is a code template for creating objects. Objects have member variables and have behaviour associated with them. In python a class is created by the keyword class. A constructor is a unique function that gets called automatically when an object is created of a class. The main purpose of a constructor is to initialise or assign values to the data members of that class. It cannot return any value other than none.

1. Default/Non-Parameterized Constructor The Python default constructor is a simple constructor which does not accept any arguments. Its definition has only one argument which is a reference to the instance being constructed. def \_\_init\_\_(self): # body of the constructor
2. Parameterized Constructor When the constructor accepts arguments along with self, it is known as parameterized constructor. def \_\_init\_\_(self, name, phone): # body of the constructor

- - -

Method

Definition: Here method is like a function. It must put inside a class & call with an object. It defines by using def keyword.

1. Activity: A method has name & it takes any parameters also it has return statement.
2. Types: In python there are three types of method
    1. Instance Method
    2. Class Method
    3. Static Method

- - -

Instance Method

Definition: In which method does not work without create an object of its class this is instance method. Instance method can access to class using self keyword.

1. Activity: This method will be called when an object is created from the class & it allows the class to initialize the attributes of a class. Is must use self keyword as a default parameter. The self keyword use for the purpose access to the attribute & methods.

- - -

Class Method

Definition: Class methods are methods that are called on the class itself, not on a specific object instance. Therefore, it belongs to a class level, and all class instances share a class method.

1. Activity: A class method is bound to the class and not the object of the class. It can access only class variables.
2. Activity: It can modify the class state by changing the value of a class variable that would apply across all the class objects.

- - -

Static Method

Definition: A static method is a general utility method that performs a task in isolation. It takes neither a self nor a cls parameter. It can be called without an object for that class, using the class name directly, also it can neither modify object state nor class state.

1. Activity: It is bound to the class and not the object of the class. Therefore, we can call it using the class name.
2. Activity: It does not have access to the class and instance variables because it does not receive an implicit first argument like self and cls. Therefore, it cannot modify the state of the object or class.

- - -
**Comparison Table**

| Feature                   | Instance Method       | Class Method               | Static Method            |
| ------------------------- | --------------------- | -------------------------- | ------------------------ |
| Bound to                  | Object (`self`)       | Class (`cls`)              | Nothing                  |
| Access instance variables | Yes                   | No                         | No                       |
| Access class variables    | Yes                   | Yes                        | No                       |
| Decorator                 | None                  | `@classmethod`             | `@staticmethod`          |
| Use case                  | Work with object data | Work with class-level data | Utility/helper functions |
| Called by                 | Object                | Class or object            | Class or object          |

Method Overloading

Definition: Methods in Python can be called with zero, one, or more parameters. This process of calling the same method in different ways is called method overloading. In easy word, in any class to use the same name of method with different parameter this is overloading.

1. Activity: This method will be called when an object is created from the class & it allows the class to initialize the attributes of a class. Is must use self keyword as a default parameter. The self keyword use for the purpose access to the attribute & methods.
2. Merits: Reduce Complexities, Improve code quality & it uses for usability & accessibility

- - -

Constructor Overloading

Definition: In any python class there are some \_\_init\_\_ method with different parameter this concept is call constructor overloading.

1. Activity: This method will be called when an object is created from the class & it allows the class to initialize the attributes of a class. Is must use self keyword as a default parameter. The self keyword use for the purpose access to the attribute & methods.
2. Merits: Reduce Complexities, Improve code quality & it uses for usability & accessibility

- - -

Operator Overloading

Definition: In python we have notice that, same built-in operator or function shows different behavior for objects of different classes, this is called Operator Overloading.

1. Activity: Suppose operator + is used to add two integers as well as join two strings and merge two lists. It is possible due to ‘+’ operator is overloaded by int class and str class. In python, we have notice that, same built-in operator or function shows different behavior for objects of different classes, this is called Operator Overloading.
2. Merits: Reduce Complexities, Improve code quality & it uses for usability & accessibility

- - -

Encapsulation

Definition: We can restrict access to methods and variable of data. This type of data prevents of direct modification of data is called encapsulation.

1. Purpose: Encapsulation provides well-defined, readable code, Prevents Accidental Modification or Deletion and Encapsulation provides security

There are three types of access modifier/specifier

| Access Modifier | Syntax       | Accessible in Own Class | Accessible in Derived Class | Accessible via Object | Example                 |
| --------------- | ------------ | ----------------------- | --------------------------- | --------------------- | ----------------------- |
| **Public**      | `variable`   | Yes                     | Yes                         | Yes                   | `self.name = "Jakaria"` |
| **Protected**   | `_variable`  | Yes                     | Yes                         | No (not recommended)  | `self._age = 25`        |
| **Private**     | `__variable` | Yes                     | No                          | No                    | `self.__salary = 5000`  |

- - -

Inheritance

Definition: Inheritance allows us to define a class that inherits all the methods and properties from another class.

1. Parent class is the class being inherited from, also called base class.
2. Child class: is the class that inherits from another class, also called derived class.

Overriding: A child class to provide a specific implementation of a method that is already provided by one of its parent classes. When a method in a child class has the same name, same parameters or signature and same return type(or subtype) as a method in its parent class, then the method in the child class is said to override the method in the parent class. We can use the overriding two ways

1. Variable Overriding: When we can replace a specific variable of parent's method by the specific variable of child's method. This type of replacement is called variable overriding
2. Method Overriding: When we can replace a specific method of parent's class by the specific method of child's method. This type of replacement is called method overriding

1. Activity: Method overriding cannot be done within a class. So,we need to derive a child class from a parent class. Hence, Inheritance is mandatory.
2. Activity: The method must have the same name as in the parent class
3. Activity: The method must have the same number of parameters as in the parent class.

- - -

Polymorphism

Definition: Polymorphism in Python is the ability of an object to take many forms. In simple words, polymorphism allows us to perform the same action in many ways. In polymorphism, a method can process objects differently depending on the class type or data type. Let’s see simple examples to understand it better.

1. Activity: Using method overriding polymorphism allows us to define methods in the child class that have the same name as the methods in the parent class. This process of re-implementing the inherited method in the child class is known as Method Overriding.
2. Activity: It is effective when we want to extend the functionality by altering the inherited method. Or the method inherited from the parent class does not fulfill the need of a child class, so we need to re-implement the same method in the child class in a different way.
3. Activity: Method overriding is useful when a parent class has multiple child classes, and one of that child class wants to redefine the method. The other child classes can use the parent class method. Due to this, we don’t need to modification the parent class code.

- - -

Abstraction

Definition: The process by which data and functions are defined in such a way that only essential details can be seen and unnecessary implementations are hidden is called Data Abstraction.

1. Why Use: This capability is especially useful in situations where a third party is going to provide implementations, such as with plugins, but can also help you when working in a large team or with a large code-base where keeping all classes in your mind is difficult or not possible.

- - -

Advance Python

- - -

Iterators

Definition: An iterator is an object that contains a countable number of values. An iterator is an object that can be iterated upon, meaning that you can traverse through all the values. Technically, in Python, an iterator is an object which implements the iterator protocol, which consist of the methods \_\_iter\_\_() and \_\_next\_\_(). An object is called iterable if we can get an iterator from it. Most built-in containers in Python like: list, tuple, string etc. are iterables.

1. Iterator vs Iterable: Lists, tuples, dictionaries, and sets are all iterable objects. They are iterable containers which you can get an iterator from.

- - -

Generators

Definition: It is fairly simple to create a generator in Python. It is as easy as defining a normal function, but with a yield statement instead of a return statement.

1. Activity: If a function contains at least one yield statement (it may contain other yield or return statements), it becomes a generator function. Both yield and return will return some value from a function.
2. Activity: The difference is that while a return statement terminates a function entirely, yield statement pauses the function saving all its states and later continues from there on successive calls.
3. Activity: when the function terminates, StopIteration is raised automatically on further calls.

- - -

Data Structure & Algorithms

Definition: It is a structure representation of data. The manupulation of storing the data in computer system's memory is known as data structure. Primarily data structure is two type Linear Data Structure and Non-Linear Data Structure.

| SL  | Linear Data Structure                         | Non-Linear Data Structure                     |
| --- | --------------------------------------------- | --------------------------------------------- |
| 1   | Array, Stack, Queue & Linked List             | Graph, Trees & Map                            |
| 2   | It is order manner                            | It is hierarchical manner                     |
| 3   | More complexity increase if database increase | Less complexity increase if database increase |
| 4   | Not memory optimize                           | Memory optimize                               |

## With Regards, `Jakir`

[![LinkedIn][linkedin-shield-jakir]][linkedin-url-jakir]
[![Facebook-Page][facebook-shield-jakir]][facebook-url-jakir]
[![Youtube][youtube-shield-jakir]][youtube-url-jakir]

### Wishing you a wonderful day! Keep in touch

<!-- Personal profile -->

[linkedin-shield-jakir]: https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url-jakir]: https://www.linkedin.com/in/jakir-ruet/
[facebook-shield-jakir]: https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white
[facebook-url-jakir]: https://www.facebook.com/jakir.ruet/
[youtube-shield-jakir]: https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white
[youtube-url-jakir]: https://www.youtube.com/@mjakaria-ruet/featured
