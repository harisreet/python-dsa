# 📘 Python DSA Summary – List, Array, Set, and Bit Manipulation

---

## 📋 List 

| Feature               | Description                                                        |
| --------------------- | ------------------------------------------------------------------ |
| **Type**              | Ordered, mutable (changeable), allows duplicates                   |
| **Syntax**            | `my_list = [1, 2, 3]`                                              |
| **Access by Index**   | Yes → `my_list[0]` returns `1`                                     |
| **Allows Duplicates** | Yes → `[1, 2, 2]` is valid                                         |
| **Common Methods**    | `append()`, `pop()`, `insert()`, `remove()`, `sort()`, `reverse()` |
| **Use Case**          | When order matters or duplicates are allowed                       |

---

## 📦 Array

| Feature               | Description                                                                 |
| --------------------- | --------------------------------------------------------------------------- |
| **Type**              | Ordered, fixed-type, more memory-efficient than list                        |
| **Syntax**            | `from array import array`<br>`arr = array('i', [1, 2, 3])`                  |
| **Access by Index**   | Yes → `arr[0]` returns `1`                                                  |
| **Allows Duplicates** | Yes                                                                         |
| **Common Methods**    | `append()`, `insert()`, `remove()`, `pop()`, `reverse()`, `buffer_info()`   |
| **Use Case**          | When you need numeric-only, fixed-type, space-efficient sequences           |

> `array('i', [...])` → `'i'` stands for integer. Other types: `'f'` (float), `'d'` (double), `'u'` (unicode char), etc.

---

## 🧮 Set

| Feature               | Description                                                          |
| --------------------- | -------------------------------------------------------------------- |
| **Type**              | Unordered, mutable, stores only unique items                         |
| **Syntax**            | `my_set = {1, 2, 3}`                                                 |
| **Access by Index**   | ❌ No indexing, since it's unordered                                  |
| **Allows Duplicates** | ❌ No → duplicates are automatically removed                          |
| **Common Methods**    | `add()`, `remove()`, `union()`, `intersection()`, `difference()`     |
| **Use Case**          | When you need to store **unique** elements or perform set operations |

---

## 🧠 Common Bitwise Operators

| Operator    | Symbol | Description             | Example         |
| ----------- | ------ | ----------------------- | --------------- |
| AND         | `&`    | 1 if both bits are 1    | `5 & 3 → 1`     |
| OR          | `\|`   | 1 if any bit is 1       | `5 \| 3 → 7`    |
| XOR         | `^`    | 1 if bits are different | `5 ^ 3 → 6`     |
| NOT         | `~`    | Inverts bits            | `~5 → -6`       |
| Left Shift  | `<<`   | Multiplies by 2^n       | `5 << 1 → 10`   |
| Right Shift | `>>`   | Divides by 2^n (floor)  | `5 >> 1 → 2`    |

---

## 📌 Summary

| Concept               | Key Feature                              |
| --------------------- | ---------------------------------------- |
| **Array**             | Fixed-type elements (use `array` module) |
| **List**              | Dynamic, heterogeneous collection        |
| **Set**               | Unordered unique elements                |
| **Bit Manipulation**  | Efficient low-level operations           |
| **Boyer-Moore Algorithm** | Efficient majority element finder    |



