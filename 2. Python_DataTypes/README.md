# Python Data Types

Data type is a pair of values and operations. \
<{set of values}, {set of operations}>

Python has rich set of predefined data types, to get type of object we can use `type()` function.

It is better to use embedded data types than create custom ones. If we need to create custom data type, better to build
it extending some predefined types.

Every value in Python is object.

## Basic Embedded Data Types
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

## Basic Number Types
* Integers: 1, 29, 3
* Floating Point Numbers: 1.9, 2.0
* Complex Numbers: 1+6j, 6+9j
* Fractions
* Decimals
* Booleans

## Object Identity, Data Type, Value
Each object has its identity, value and type, each object representation is called value, identity is created on object 
creation and is identifying object among others, each object has its data type.

## Primitive Vs Non-Primitive Data Types
Primitive data types are mostly created as data type simplification. \
Primitive data types are mostly atomic types, that cannot be composed of other data types or has no connections to other 
data types and have fixed size of memory for values.

Number types are primitive in most programming languages, but not in Python.

Non-Primitive data type are also called Reference Data Types as we work with their values by reference not by values.
Python works with Non-primitive data types.

## Mutable & Immutable Data types
Mutables are objects which value can change, Immutable objects value can't change, new object is created instead. \
Immutability brings safety and optimization possibility \
Mutability brings usage freedom. \
Immutable objects are safe for usage by multiple variables as there will be only reading operation for them.

## Container Data types
Object that can contain reference to other objects are called container objects, array type objects are container objects.

## Booleans
Bool type has 2 values: **True** and **False** \
True and False are just 1 and 0 with some additional features. Other values can be converting to boolean using truth testing
procedure with `bool()` function. \
Bool is subclass of int.

## Numbers of different notations
Python store number by default in decimal notation, but also allows to store numbers in hexadecimal, octal or binary
notations.

* 0b101 - binary
* 0o21 - octal
* 0xF6 - hexadecimal

## None
Nothing, none is object, it's a keyword referring to `null` concept.

## Decimals
Decimals allows to define floating-point numbers with fixed number of digits after dot. Simple float has problems with results because of hardware limitations, in this case decimals also can be useful.

## Fractions
Fractions allows to define rational numbers (numerator and denominator), we can perform mathematical expressions for such values using =,-, etc.

## None vs NaN vs Undefined
If variable doesn't exist, it's undefined. When variable is created it can have value, Nan or None. Working with undefined variable generates error.

## Array
Array is ordered sequence of elements, Python array main representations are Strings, Lists, Tuples. \
Array components:
* Index (starts from 0)
* Elements

## Lists
List is ordered flexible (mutable) array of objects that can have different types, and can be modified. \
We can concatenate (merge) lists which creates new list and we can concatenate with other lists. \
Lists can be nested inside each other and also we can add nested list. Using nested list we can build matrices, for bigger matrix operations is better to use external modules like Numpy. \
As I mentioned before lists are mutable, so they can be modified and when we modify a list, the list itself is changed. \
`list()` function allows to create a list from iterable object. \
If we try to access element by index that is not filled we will get `Out of range` error.

## Strings
String is ordered sequence of characters (characters array), String type pseduonym is `str` and by default strings in
Python 3 are encoded using **Unicode**

String values can be placed either in single quotes or in double quotes. Single quotes strings can contain double quotes
and vice versa.

Multiline strings can be places in triple quotes. We can use single quotes and double quotes in triple quotes strings 
without escape sequences. Triple quotes are often used to create multi-line comments.

We can define the step with which elements will be extracted to subarray from original array. \
arr[start:end:step] - extract elements from start to end indexes with step

Concatenating strings is performed using + operator and string repetition can be performed using * operator

By default, strings in Python are immutable: Each modification of string creates a new string(not changes the old one)

Some types in Python are immutable(Strings, Numbers, Tuples)

## Escape Sequences
Escape sequences are used to place quotes in single-quoted string or for double-quoted ones, or for using special character.
Escape sequences starts from " \ " symbol. \
There are different special characters:
* \n - new line
* \t - tabulation

Sometimes escape sequences are not convenient, to suppress escape sequences we can use `r` in front string.

## Dictionary
Dictionary is a collection of <key.value> pairs (mapping from key to value). \
Dictionary element don't have predefined order. Key can be value of immutable type. \
Dictionary can be modified (mutable). \
Dictionary is implemented as hash table (data structure that has high performance on access by key) \
We can modify dictionary accessing elements by key, when we assign value to non-existing key, it's created new one. \
We can't predict the order of dictionary elements, we can get dictionary keys as list and the iterate over them.

## List & Dictionaries
* List is ordered collection of references to objects.
* Dictionary is unordered collection of references to objects supporting access by key.

## Nested Dictionary
Each value of dictionary can also be a dictionary.