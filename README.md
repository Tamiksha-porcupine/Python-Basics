# Python Fundamentals

A structured repository of beginner-to-intermediate Python programming notebooks. Each folder contains a focused code file and its own dedicated README explaining the concepts covered. This repository serves as a clean, practical reference for core Python topics built from hands-on practice and real code execution.

---

## Repository Structure

```
Python-Fundamentals/
│
├── Strings/
│   ├── Strings.ipynb
│   └── README.md
|
├── Integers-and-Floats/
│   ├── Python-Integers-Float.ipynb
│   └── README.md
│
├── Lists-Tuples-Sets/
│   ├── Lists-Tuples-Sets.ipynb
│   └── README.md
```

---

## What This Repository Covers


### Strings — Indexing, Searching, and Positioning

Covers the string data type in depth, with a focus on how Python positions and retrieves individual characters.

**Topics included:**
- Declaring strings with single and double quotes
- `len()` function: counting characters including spaces
- Positive indexing: left-to-right access starting at index `0`
- Negative indexing: right-to-left access starting at index `-1`
- Dynamic indexing using `len(text) - 1`
- `IndexError` — what happens when an index is out of range (tested and documented)
- `str.count()` — counting character occurrences
- `str.index()` — finding the position of a character (raises `ValueError` if not found)
- `str.find()` — safe character search (returns `-1` if not found)
- Difference between `.index()` and `.find()` — tested with examples
- `str.rindex()` — searching from the right side to find the last occurrence
- Finding the second occurrence of a character using a start-position argument in `.index()`
- Real-world string parsing example: extracting values from structured strings like `"ID:9482-NAME:Alex"`

---

### Integers and Floats — Operators, Type Casting, and String Methods

Covers the numerical foundation of Python programming along with type conversion and string manipulation utilities.

**Topics included:**
- Arithmetic operators: addition, subtraction, multiplication, division, floor division, modulus, and exponentiation
- Using variables with all arithmetic operations
- Built-in numeric functions: `abs()` and `round()`
- Comparison operators: `==`, `!=`, `>`, `<`, `>=`, `<=` — both direct and variable-based
- Operator chaining
- Type Casting: converting strings to integers, integers to strings, and understanding float-to-int truncation behavior
- String `.split()` method: splitting by spaces, commas, hashes, and custom delimiters
- String `.join()` method: reassembling lists back into strings with a custom delimiter
- Practical use case: extracting numbers from strings like `"100 followers"`
---

## Key Concepts at a Glance

| Concept | Notebook |
|---|---|
| Arithmetic & Comparison Operators | Integers and Floats |
| Type Casting (int, str, float) | Integers and Floats |
| `.split()` and `.join()` | Integers and Floats |
| String Length with `len()` | Strings |
| Positive and Negative Indexing | Strings |
| `.index()` vs `.find()` | Strings |
| `.rindex()` and Multi-occurrence Search | Strings |
| IndexError and ValueError handling | Strings |

---

### Lists, Tuples, and Sets — Data Structures, Methods, and Mutability

Covers the foundational collection types in Python programming, focusing on sequence manipulation, performance optimization, and unique data filtering.

**Topics included:**
- List Basics: Creating lists, indexing, slicing, and checking for item existence using the in operator
- Modifying Lists: Appending items, inserting at specific indices, and extending lists with another collection
- Ordering and Sorting: Sorting lists in-place with .sort(), using the sorted() function, and reversing order
- String Conversions: Transforming lists into strings using .join(), and turning strings into lists using .split()
- The Mutability Trap: Understanding how list assignments create references, and how modifying one affects the other
- Tuples: Creating immutable sequences, exploring their performance benefits, and understanding why they lack modification methods
- Sets and Uniqueness: Creating sets, automatically eliminating duplicates, and adding or updating elements
- Set Operations: Leveraging powerful mathematical operations like .intersection(), .difference(), and .union()


---

## Who This Is For

- Anyone starting out with Python and building a strong foundation
- Students revisiting core concepts before moving into data science or machine learning
- Developers who want a clean, no-fluff reference for Python basics

---

## Author
**Tamiksha Sharma**
