# 📘 Python DSA Summary – Stack , Queue and Deque

---
## 🗂️ Stack

| Feature               | Description                                          |
| ---------------------|------------------------------------------------------|
| **Type**              | LIFO – Last In, First Out                            |
| **Built-in Support**  | Use `list` or `collections.deque`                   |
| **list**              | `push → append()`, `pop → pop()`                     |
| **queue.LifoQueue**   | `push → put()`, `pop → get()`                     |
|**Use Case**          | Undo operations, backtracking, expression parsing   |

---
## 📥 Queue

| Feature              | Description                                 |
| -------------------- | ------------------------------------------- |
| **Type**             | FIFO – First In, First Out                  |
| **Built-in Support** | Use `collections.deque` or `queue.Queue`    |
| **list**             | `enqueue → append()`, `dequeue → popleft()` |
| **queue.Queue**      | `enqueue → put()`, `dequeue → get()`        |
| **Use Case**         | Scheduling, buffers, BFS traversal          |

---
## 🔁 Deque (Double-Ended Queue)

| Feature              | Description                                      |
| -------------------- | ------------------------------------------------ |
| **Type**             | Elements can be added/removed from both ends     |
| **Built-in Support** | `collections.deque`                              |
| **Common Methods**   | `append()`, `appendleft()`, `pop()`, `popleft()` |
| **Use Case**         | Sliding window problems, palindrome checking     |
