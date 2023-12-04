# Iteration in Python

## Overview

Iteration is a fundamental programming concept that allows you to repeatedly execute a block of code. In Python, there are several ways to implement iteration, providing flexibility and efficiency in handling collections of data or performing repetitive tasks.

This chapter explores the various methods of iteration in Python, ranging from traditional `for` and `while` loops to more advanced techniques using iterators and generators.

## Contents

1. **`for` Loops:**

   - Introduction to `for` loops and their syntax.
   - Iterating over sequences (lists, tuples, strings).
   - Using the `range` function for numeric iteration.

2. **`while` Loops:**

   - Understanding the `while` loop structure.
   - Implementing conditional-based iteration.
   - Pitfalls and best practices.

3. **Iterators:**

   - Exploring the iterator protocol.
   - Creating custom iterators.
   - Understanding the `iter()` and `next()` functions.

4. **Generators:**

   - Introduction to generator functions.
   - Yielding values in a lazy and memory-efficient manner.
   - Use cases and advantages over traditional functions.

5. **`enumerate` and `zip`:**

   - Simplifying iteration with `enumerate`.
   - Simultaneous iteration over multiple sequences with `zip`.

6. **Iterating Through Dictionaries:**
   - Strategies for iterating through keys, values, and key-value pairs.
   - Utilizing dictionary comprehension.

## Examples

### Example 1: Using `for` Loop to Iterate Over a List

```python
fruits = ['apple', 'banana', 'cherry']
for fruit in fruits:
    print(fruit)
```

### Example 2: Creating a Simple Generator Function

```python
def countdown(n):
    while n > 0:
        yield n
        n -= 1

for num in countdown(5):
    print(num)
```
