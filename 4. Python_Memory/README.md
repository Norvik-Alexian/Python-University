## Memory Handling in Python
Python interpreter mostly manages the memory, we should not reserve memory, clean memory, etc.

Python deletes unwanted objects (built-in types or class instances) automatically to free the memory space. The process by which Python periodically frees and reclaims blocks of memory that no longer are in use is called `Garbage Collector`.

### How GC decides to remove object.
GC checks if references count is 0, also checks if existing references are cyclical references.(object refers to itself, then counter will never be 0 and memory leaks are possible if not check such situations)

### Garbage Collector Checking Regularity
GC usually checks the objects based on their lifetime:
* New objects are checked very often
* Not so new objects are checked more rarely
* Old objects are checked very rarely

## Memory Addresses Management
Besides returning unique object identifier id() returns starting address working with CPython, In Pypy and Jython it's just identifier. \
Python doesn't support pointers (variables that store addresses of another variable).

## References to Object
One object can have multiple references to it. \
An object reference count increases when it is assigned a new name or placed in a container. \
The object references count decreases when it's deleted with del, its reference is reassigned, or its reference goes out of scope.

Local identifiers are automatically deleted. \
Global identifiers should be freed manually (decrease global identifiers usage)

## Memory Optimization: Python Interning
Interning is re-using the objects on-demand instead of creating new objects. \
The CPython implementation of Python pre-allocates shared values, certain ranges of commonly-used immutable types. \
When Python is instructed to instantiate a new immutable object, it first checks to see if an identical object already exists as a shared object.

### Strings Interning Runtime/Compile Time
A string will not be interned unless it is loaded at compile time as a constant string. This includes strings defined as expressions, remember that an expression is evaluated first before an object is instantiated.

Any string constructed at runtime will not be interned.

## Mutable/Immutable Object Ids
* The value of an immutable object is tied to its identity, if the value changes, the object changes.
* The value of a mutable object is not tied to its identity, identity is retained across changes made to the object.