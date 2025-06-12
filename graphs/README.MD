# 📘 Graph Representations in Python

## ⚖️ Adjacency List vs Adjacency Matrix

| Feature                         | **Adjacency List**          | **Adjacency Matrix**                   |
| ------------------------------ | --------------------------- | -------------------------------------- |
| **Best For**                    | Sparse graphs               | Dense graphs                           |
| **Edge Lookup (i → j exists?)**| Slower: `O(degree)`         | Fast: `O(1)`                           |
| **Space Complexity**           | Efficient: `O(V + E)`       | Heavy: `O(V²)`                         |
| **Graph Traversal (BFS/DFS)**  | Fast: `O(V + E)`            | Slower: `O(V²)`                        |
| **Adding Vertex**              | Fast: `O(1)`                | Slow: `O(V²)` (requires resizing)      |
| **Removing Vertex**            | Moderate: `O(V + E)`        | Slow: `O(V²)`                          |
| **Adding/Removing Edge**       | `O(1)` (list append/remove) | `O(1)` (direct access)                 |
| **Checking Neighbors**         | Fast: `O(degree)`           | Slow: `O(V)` (must scan row)           |
| **Directed or Undirected**     | Both supported easily       | Both supported easily                  |
| **Weighted Graphs**            | Easy to store weights       | Easy to store weights as matrix values |

---

## 🔍 Graph Traversal

### 📌 BFS (Breadth-First Search)
- Explores the graph **level by level**
- Uses a **queue**
- Best for **shortest path in unweighted graphs**

### 📌 DFS (Depth-First Search)
- Explores **as far as possible** along each branch before backtracking
- Uses **recursion** or a **stack**
- Useful for **pathfinding**, **connected components**, and **cycle detection**

---

