# 📘 Linked Lists 

---

## 📋 Types of Linked Lists

| Type                | Description                               |
|---------------------|-------------------------------------------|
| **Singly Linked List**  | One pointer (next) per node                |
| **Doubly Linked List**  | Two pointers (next, prev) per node         |
| **Circular Linked List**| Last node points to the head (circular)   |

---

## ⏱️ Time Complexities (Singly Linked List)

| Operation              | Time Complexity (Avg/Worst) |
|------------------------|-----------------------------|
| Insertion at Head      | O(1)                         |
| Insertion at End       | O(n)                         |
| Deletion by Value      | O(n)                         |
| Search                 | O(n)                         |

---

## 📊 Python `list` vs Custom `Linked List`

| Feature / Operation        | `list` (Built-in)                 | `Linked List` (Custom)                                     |
|----------------------------|-----------------------------------|------------------------------------------------------------|
| **Storage**                | Contiguous memory (array)         | Nodes scattered in memory, linked via pointers             |
| **Indexing**               | ✅ O(1) – Direct access via index  | ❌ O(n) – Must traverse to reach index                      |
| **Insertion at End**       | ✅ Amortized O(1) (`append`)       | ✅ O(1) if tail is maintained; else O(n)                    |
| **Insertion at Beginning** | ❌ O(n) – Shifting required        | ✅ O(1) – Just re-link head                                 |
| **Insertion in Middle**    | ❌ O(n) – Shifting required        | ❌ O(n) – Need to traverse                                  |
| **Deletion at End**        | ✅ O(1) (`pop()`)                  | ❌ O(n) unless tail + prev maintained                       |
| **Deletion at Beginning**  | ❌ O(n) – Shifting required        | ✅ O(1) – Just move head                                    |
| **Deletion in Middle**     | ❌ O(n) – Need shifting            | ❌ O(n) – Need traversal and re-linking                     |
| **Search by Value**        | ❌ O(n)                            | ❌ O(n)                                                     |
| **Dynamic Resizing**       | ✅ Auto handled                    | ✅ Auto handled (by design)                                 |
| **Memory Efficiency**      | ❌ Wastes space in resizing        | ✅ Efficient for frequent inserts/deletes                   |
| **Use Case**               | Best for random access / indexing | Best for dynamic data where insertion/deletion is frequent |





