# 🌳 Tree Time Complexities and Summary

---

## 🌳 Tree Traversal Summary Table

| Traversal Type  | Order of Visit       | Time Complexity | Space Complexity | Use Case / Example                         |
|------------------|----------------------|------------------|-------------------|---------------------------------------------|
| **Inorder**       | Left → Root → Right  | O(n)             | O(h)              | BST → Sorted output                         |
| **Preorder**      | Root → Left → Right  | O(n)             | O(h)              | Clone/Copy tree, Expression tree to prefix  |
| **Postorder**     | Left → Right → Root  | O(n)             | O(h)              | Delete tree, Evaluate expression trees      |
| **Level Order**   | Level by level (BFS) | O(n)             | O(w)              | Shortest path in unweighted tree            |

> - `n` = number of nodes  
> - `h` = height of the tree  
> - `w` = maximum width of the tree

---

## 🌲 Tree Operation Time Complexities

| Data Structure            | Search         | Insert         | Delete         | Traversal      |
|---------------------------|----------------|----------------|----------------|----------------|
| **Binary Tree**           | O(n)           | O(n)           | O(n)           | O(n)           |
| **Binary Search Tree**    | O(log n) / O(n)| O(log n) / O(n)| O(log n) / O(n)| O(n)           |
| **Balanced BST (AVL / Red-Black)** | O(log n) | O(log n)      | O(log n)      | O(n)           |

> - Balanced BST ensures better performance by keeping the height ≈ log(n)  
> - Unbalanced BST can degrade to O(n) (like a linked list)

---

📌 **Bonus Tip**: For space complexity in recursive traversals, worst-case is O(n) (for skewed trees), best-case is O(log n) (for balanced trees).

