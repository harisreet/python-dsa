# 🗂️ HashMap in Python – Notes

## 📘 Definition
A **HashMap** is a data structure that stores data in **key-value pairs**.

In Python, a `dict` is the built-in implementation of a HashMap.

---

## 🧠 Common Operations & Their Time Complexity

| Operation         | Time Complexity (Average) |
|------------------|----------------------------|
| Insert / Update  | `O(1)`                     |
| Lookup           | `O(1)`                     |
| Delete           | `O(1)`                     |
| Check Key Exists | `O(1)`                     |
| Iterate          | `O(n)`                     |

> 🔎 **Note:** Worst-case time is `O(n)` due to hash collisions, but Python handles this efficiently using **good hash functions and dynamic resizing**.

---

## ✅ When to Use a HashMap

- When you need **fast lookup**, **insertion**, or **deletion** by key.
- To **count frequencies**, e.g., characters, words, or elements.
- To **map keys to values** efficiently.
- To **group or classify data** based on certain criteria.

---

