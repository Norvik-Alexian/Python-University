## For Loop

for allows to iterate over elements of array, on each iteration target gets the value of next object element. \
Using **for** we can iterate over string characters, on each iteration next character in string is placed inside char identifier

## List Comprehension Expression
Comprehension expression consists of brackets containing an expression followed by a for clause, then zero or more for
or if clauses. \
`Format: [<expression><for clause><for or if clause>]`

The result will be a new list resulting from evaluating the expression in the context of the for and if clauses which
follow it.

To generate new lists based on existing ones we can use comprehension expressions.

## Timeit
This module provides a simple way to find the execution time of small bits of Python code. \
Mesuring time before and after running method is not precise as there might be a background process momentarily running
which disrupts the code execution and you will get significant variations in the running time of small code snippets. \
timeit runs your snippet of code millions of times so that you get the statistically most relevant measurement of code 
execution time.

The module function timeit.timeit(stmt, setup, timer, number) accepts four arguments:
* stmt - which is the statement you want to measure, it defaults to 'pass'
* setup - which is the code that you run before running the stmt, we generally use this to import the required modules
for our code.
* timer - which is timeit.Timer object, it usually has a sensible default value, so you don't have to worry about it.
* number - which is the number of executions you'd like to run the stmt

Where the timeit.timeit() function returns the number of seconds it took to execute the code.

## If/elif/else
To check conditions in Python we can use if/elif/else, only if is mandatory elif and else are optional. \
To check multiple conditions we can use **and** and **or** keywords.

## Object Methods
Method is a function specific for object of some specific type, to call method on some object we use following format: \
`obj.methodName()`
