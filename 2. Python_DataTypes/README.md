## Python Data Types

Data type is a pair of values and operations. \
<{set of values}, {set of operations}>

Python has rich set of predefined data types, to get type of object we can use `type()` function.

It is better to use embedded data types than create custom ones. If we need to create custom data type, better to build
it extending some predefined types.

Every value in Python is object.

### Basic Embedded Data Types
1. Numbers
2. Strings
3. Lists
4. Dictionaries
5. Tuples
6. Sets
7. Logic Values
8. None
9. Files
10. Program Elements

### Basic Number Types
* Integers: 1, 29, 3
* Floating Point Numbers: 1.9, 2.0
* Complex Numbers: 1+6j, 6+9j
* Fractions
* Decimals
* Booleans

### Object Identity, Data Type, Value
Each object has its identity, value and type, each object representation is called value, identity is created on object 
creation and is identifying object among others, each object has its data type.

### Primitive Vs Non-Primitive Data Types
Primitive data types are mostly created as data type simplification. \
Primitive data types are mostly atomic types, that cannot be composed of other data types or has no connections to other 
data types and have fixed size of memory for values.

Number types are primitive in most programming languages, but not in Python.

Non-Primitive data type are also called Reference Data Types as we work with their values by reference not by values.
Python works with Non-primitive data types.

### Mutable & Immutable Data types
Mutables are objects which value can change, Immutable objects value can't change, new object is created instead. \
Immutability brings safety and optimization possibility \
Mutability brings usage freedom. \
Immutable objects are safe for usage by multiple variables as there will be only reading operation for them.

### Container Data types
Object that can contain reference to other objects are called container objects, array type objects are container objects.

### Booleans
Bool type has 2 values: **True** and **False** \
True and False are just 1 and 0 with some additional features. Other values can be converting to boolean using truth testing
procedure with `bool()` function. \
Bool is subclass of int.

### Numbers of different notations
Python store number by default in decimal notation, but also allows to store numbers in hexadecimal, octal or binary
notations.

* 0b101 - binary
* 0o21 - octal
* 0xF6 - hexadecimal

### None
Nothing, none is object, it's a keyword referring to `null` concept.

### Decimals
Decimals allows to define floating-point numbers with fixed number of digits after dot. Simple float has problems with results because of hardware limitations, in this case decimals also can be useful.

### Fractions
Fractions allows to define rational numbers (numerator and denominator), we can perform mathematical expressions for such values using =,-, etc.