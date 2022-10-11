## Language Introduction
Python is dynamic interpreted (bytecode compiled) language, put it simply Python is compiled-interpreted Programming
language. Python support OOP, structured programming and other approaches.
Python trackes the types of all values at runtime and flags code that does not make sense as it runs.

**_Identifier_** in Python is pseudonym for variable, function class, module or some other objects

Python operations can be performed by:
* operators
* specific functions

### Python Data Typing
Python Typing:
* Dynamic Typed (type of variable can change)
* Strongly Typed (value can be associated with one specific type)
* Implicitly Typed (Type of variable shouldn't be declared explicitly)

### Python Indentation
One unusual Python feature is that the whitespace indentation of a piece of code affects its meaning.
According to the official Python style guide you should indent 4 spaces.

### Python Module
Module is the file with Python code and `.py` extension.
Program can call another program after importing them, when we import a module it's being executed.
Import works once for each module, even if it was called several times.

Module is used as library, Module is considered as set of variables names also called namespace.
Each variable name from namespace is called attribute.
Attribute is a variables related to some object like module.

Modular structure with differentiated namespaces allows to avoid name conflicts and makes code more simple dividing
complex construction into smaller chunks.

### Scripts Vs Program
Script vs Program: script is small and simple program \
Python can be considered for both writing scripts or bigger programs.

### Python Keywords
Keyword is a word that is reserved by a program because the word has a special meaning. Keywords can be command or 
parameters. Every programming language has a set of keywords that cannot be used as a variable names. Keywords sometimes
called reserved names.

### Constants Identifiers
Constant is a type of variable whose value cannot be changed and Python doesn't support constant by default.

### Computer Science 
Computer science is the study of both computer hardware and software design.
Computer science encompasses both the study of theoretical algorithms and the study of implementing them through computer
hardware and software 

### Python as Imperative Programming Language
Python is imperative programming language, imperative is a programming paradigm in which program statements define steps
that describe how to solve the problem.

Declaritive is a programming paradigm in which program statements define the desired output of program.
Different programming languages are good for differnet cases.

### Python Program Elements
* Program is represented by modules.
* Modules contains statements.
* Statements contains expressions.
* Expressions create or modify objects.

### Why Python?
1. High development speed(scripting, no defined types, less efforts required)
2. Code quality
3. Universality
4. Cross-Platform (interpreter for different OS)
5. Reach set of libraries
6. Powerful Community

### Python Weaknesses
1. Low performance (program running on Python is slower than on many other languages)
2. Different types of developers
3. Possible different code style at same project or file can decrease code quality

### Python Platform Features
* OOP support (Polymorphism, inheritance, overriding and etc.)
* Procedural programming support
* Free and open source
* Portable

### Python Programming Features
* Dynamic typing
* Automatic memory control (garbage collector)
* Modular Architecture
* Embedded Data Types
* Embedded Operations
* Embedded Library
* External Library

### Interpreting & Compiling Code
Compilation is the process of translating the whole program into some another language. \
Interpretation is process of translation and execution of program statement by statement using Virtual Machine. \
Each platform can have its own interpreter.

### How Python code is executed
1. Python code is translated into bytecode
2. Bytecode is transferred to PVM (Python Virtual Machine) for interpreting

### Bytecode Vs Machine Code
Machine code is set of instructions which can be directly executed by processor. \
Bytecode is set of instructions which can be executed by some virtual machine. \
Python bytecode is a special optimized format for storing Python code. Bytecode is platform independent, bytecode works 
faster than original Python code.\
Interpreter interprets bytecode (translate to machine code and executes it)

### Python Virtual Machine (PVM)
PVM executes Python bytecode interpreting it, CPython is a standard implementation of PVM.

### JIT
JIT (Just In Time Compilation) \
Sometimes it's better to convert code to machine code and execute it without conversion each time. \
JIT compiler allows to perform such execution. There are some implementations of JIT for Python like Numba.

### What is program?
* Data
* Operations

### What is Python program?
Program in Python is a set of operations on some objects and data is represented by Python objects. \
Operations in Python are represented by operators and functions.
