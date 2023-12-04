# Sequence Type in Python

A sequence type in Python refers to a built-in data type that represents an ordered collection of items. Each item in the sequence is assigned a unique index, starting from 0 for the first element. Sequences are an essential part of Python programming, and they provide a versatile way to organize and manipulate data.

## Characteristics of Sequence Types

1. **Ordering:**

   - Elements in a sequence are stored in a specific order, and this order is maintained throughout the sequence.

2. **Indexing:**

   - Each element in the sequence can be accessed using its index. Positive indices refer to elements from the beginning, and negative indices refer to elements from the end.

3. **Slicing:**

   - Sequences support slicing, allowing you to create new sequences by extracting a portion of an existing sequence.

4. **Iteration:**

   - Sequences can be iterated using loops or other iterable constructs, making it easy to process each element in the sequence.

5. **Immutability vs. Mutability:**

   - Some sequence types, like tuples and strings, are immutable, meaning their elements cannot be changed after creation. Others, like lists, are mutable, allowing for dynamic modifications.

6. **Common Sequence Types:**
   - **Lists (`list`):** Mutable sequence, allows for dynamic resizing and modification of elements.
   - **Tuples (`tuple`):** Immutable sequence, commonly used for fixed collections of elements.
   - **Strings (`str`):** Immutable sequence of characters.
   - **Ranges (`range`):** Immutable sequence representing an arithmetic progression of integers.

## Examples of Sequence Operations

### Creating Sequences

```python
# List
my_list = [1, 2, 3, 4, 5]

# Tuple
my_tuple = (10, 20, 30, 40, 50)

# String
my_string = "Python"

# Range
my_range = range(0, 10, 2)
```

### Accessing Elements

```python
# Indexing
first_element = my_list[0]

# Negative Indexing
last_element = my_tuple[-1]
```

### Slicing

```python
# Slicing
subset = my_string[1:4]
```

### Iterating Through Elements

```python
# Iterating
for element in my_range:
    print(element)
```

### Modifying Mutable Sequences

```python
# Modifying List
my_list.append(6)
my_list[0] = 0
```
