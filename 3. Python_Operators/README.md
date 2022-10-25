## Python Operators

Operators are operations pseudonym.

Operators:
* `Unary` - 1 operand, example: -number
* `Binary` - 2 operands, example: number1 + number2
* `ternary` - 3 operands, example: x if condition else y

### Numbers Operators
Like many other languages supports operators for working with numbers: +, -, *, /, %, **, etc.

Operators have priorities(* has higher priority than +) and `()` can be used for grouping operations.

### Division Operator
There are 2 types of division:
1. `/` division that result floating-point
2. `//` division that rounds the result down to integer if operands are whole numbers and results floating point in
other case.

### Expressions and Mixed types
Python expressions can include numbers of different types than the values are converted to the most complex type from them.

complexity rule: int < float < complex

### Boolean expressions
Logical expressions using comparison operators. \
comparison operator: >, <, ==, != \
we can use mixed types of numbers for comparison.

### Boolean Specific Operators
* and
* or 
* not

### Complex Comparison
Python allows to compound comparison operators, it allows to check the range.

Example: a < b < c is equivalent to a < b and b < c

### Often used False Values (Falsy)
* None
* False
* Zero of any numeric types
* Empty sequences and collections

### Unfixed Size Whole Numbers
Python allows to declare as big as whole numbers as memory allows.

### Bitwise Operators 
* <<, >>, &, |, ^
* x << 2

Better to avoid such operations in Python.

### Operators Overriding
Each operator can perform different operation in case of different type values, we can override operator for our custom type to define how it will perform.

Overriding is based on Polymorphism.(one form different implementations)

### Operations on Arrays: Basic Operations
* Getting length: len(arr)
* Getting element at some position: arr[index]
* Getting element with negative index: arr[-index]

### Operations on Array: Slicing
* Getting subarray: arr[startIndex:endIndex]
* Getting subarray with default boundaries
* arr[Start:End:Step]
We can define the step with which elements will be extracted to subarray from original array.
