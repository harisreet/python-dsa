# 📘 Linked Lists 

---

## 📋 Types of Linked Lists

| Type                  | Description                               |
|------------------------|-------------------------------------------|
| **Singly Linked List** | One pointer (`next`) per node             |
| **Doubly Linked List** | Two pointers (`next`, `prev`) per node    |
| **Circular Linked List**| Last node points to the head (circular)  |

---

## ⏱️ Time Complexities (Singly Linked List)

| Operation           | Time Complexity (Avg/Worst) |
|---------------------|-----------------------------|
| Insertion at Head   | O(1)                         |
| Insertion at End    | O(n)                         |
| Deletion by Value   | O(n)                         |
| Search              | O(n)                         |

---

## 🔄 Time Complexity: Python `list` vs `Linked List`

| Operation        | Python List (Dynamic Array) | Linked List (Singly)       |
|------------------|-----------------------------|-----------------------------|
| `append()`       | O(1)*                        | O(n) *(need to traverse)*   |
| `prepend()`      | O(n) *(shift elements)*      | O(1)                        |
| `insert(i, x)`   | O(n) *(shift elements)*      | O(n) *(traverse to index)*  |
| `pop()` (last)   | O(1)                         | O(n) *(traverse to end)*    |
| `pop(0)`         | O(n) *(shift all elements)*  | O(1)                        |
| `remove(value)`  | O(n)                         | O(n)                        |
| `access(index)`  | O(1)                         | O(n)                        |
| `access(value)`  | O(n)                         | O(n)                        |

> 📝 *Python’s `list.append()` is amortized O(1) because resizing only happens occasionally when capacity increases.*

---

## ✅ Summary

- Use **Linked Lists** when:
  - You need frequent insertions/deletions
  - You don’t need fast indexing

- Use **Python Lists** when:
  - You require fast access via index
  - Your data is mostly static or accessed in order
