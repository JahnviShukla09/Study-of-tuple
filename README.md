# Experiment 4: Working with Python Tuples

## 1. Aim
To understand and implement **Python Tuples**, focusing on their immutability, indexing, concatenation, and their application in fixed data scenarios such as attendance tracking and student records.

---

## 2. Theory
A **Tuple** is a collection which is **ordered** and **immutable** (unchangeable). They are written with round brackets `()`.

### Key Characteristics:
* **Immutability:** Once a tuple is created, you cannot change, add, or remove items. This makes them faster and safer for data that shouldn't change.
* **Packing and Unpacking:** Tuples allow you to store multiple values in one variable (packing) and extract them back into individual variables (unpacking).
* **Memory Efficient:** Because they are static, tuples are more memory-efficient than lists.
* **Singleton Tuple:** To create a tuple with only one item, you must add a trailing comma (e.g., `y = ("orange",)`), otherwise Python sees it as a string.

[Image of Python tuple immutability and memory efficiency comparison]

---

## 3. Steps / Procedure
1.  **Creation & Constraints:** Define tuples and attempt to use list methods like `.append()` to observe the `AttributeError`, confirming immutability.
2.  **Slicing:** Use the `[start:stop:step]` syntax to extract specific patterns from numerical tuples.
3.  **Concatenation:** Update a tuple by adding another tuple to it using the `+=` operator (creating a new tuple in the background).
4.  **Iteration & Calculation:** Use `for` loops and
