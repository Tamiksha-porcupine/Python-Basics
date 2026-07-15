#Python Fundamentals: Lists, Tuples, and Sets
A comprehensive, hands-on exploration of Python's core data structures: Lists, Tuples, and Sets.
This repository contains a Jupyter Notebook designed to demystify indexing quirks, mutability 
loopholes, memory allocation behaviors, and data structure performance tradeoffs.

##Key Concepts Covered
###List Modification: Understanding in-place operations (.append(), .extend()) and how state persistence in Jupyter can lead to unexpected list compounding.
###Nested Indexing: Accessing elements buried inside multi-dimensional collections using nested notation (list[i][j]).
###Memory References & Mutability: Navigating Python’s assignment pointer behaviors (list_b = list_a), and differentiating between shallow copies and deep copies.
###Tuple Immutability: Discovering how a technically "immutable" tuple can still have its contents altered if it references a mutable collection.
###Set Operations & Optimization: Working with mathematical operations (unions, differences) and analyzing the dramatic 
algorithmic performance differences between lists and sets.

##1. Nesting vs. Extending Lists
Adding multiple elements to a list can be done in two ways, resulting in fundamentally different structural outputs:
.extend(): Merges the target list's elements directly into the original list (flat structure).
.append(): Inserts the new collection as a single, nested list object (multi-dimensional structure).
To search for a nested item, Python's standard **in** membership operator only checks top-level items

##2. Preventing Object Aliasing and Shallow Copying Issues
When duplicating structures in Python, simple assignment (=) creates a new reference pointer rather
than a new object.

###Shallow Copy (.copy() or [:]): Creates a new outer list, but continues pointing to 
original memory addresses for any nested lists.
###Deep Copy (copy.deepcopy()): Recursively copies every single object inside the list, 
ensuring 100% independence.

##3. The Tuple Mutability Loophole
Tuples are defined as immutable (the contents of their elements cannot be swapped or deleted).
However, if an element inside a tuple points to a mutable object (like a list), the contents
of that list can still be modified.
