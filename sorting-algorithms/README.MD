# **🔹Sorting Algorithm Summary🔹**
---

| **Sorting Algorithm** | **Average Time Complexity** | **Worst Time Complexity** | **Space Complexity** | **In-Place?** | **Stable?** | **Best Use Case**                                            |
| --------------------- | --------------------------- | ------------------------- | -------------------- | ------------- | ----------- | ------------------------------------------------------------ |
| **Bubble Sort**       | O(n²)                       | O(n²)                     | O(1)                 | Yes           | Yes         | Small or nearly sorted lists                                 |
| **Selection Sort**    | O(n²)                       | O(n²)                     | O(1)                 | Yes           | No          | Small lists or when memory is limited                        |
| **Insertion Sort**    | O(n²)                       | O(n²)                     | O(1)                 | Yes           | Yes         | Small or nearly sorted lists                                 |
| **Merge Sort**        | O(n log n)                  | O(n log n)                | O(n)                 | No            | Yes         | Large data sets; stability desirable                         |
| **Quick Sort**        | O(n log n)                  | O(n²) (worst, rare)       | O(log n)             | Yes           | No          | Large data sets; in-place algorithm                          |
| **Heap Sort**         | O(n log n)                  | O(n log n)                | O(1)                 | Yes           | No          | Large data sets; in-place algorithm without additional space |

---

# **🔹 heapq — Definition and Functions 🔹**

| **Aspect**                       | **Description**                                                                                                                                                      | **Time Complexity** |
| -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- |
| **Module**                       | `heapq`                                                                                                                                                              |                     |
| **Definition**                   | `heapq` provides a set of **heap operations implemented on ordinary lists**. Heaps enable efficiently retrieving or adding elements while retaining a partial order. |                     |
| **Heap Type**                    | **Min-Heap** by default                                                                                                                                              |                     |
| **heapq.heapify(arr)**           | Transforms a list into a min-heap in place                                                                                                                           | O(n)                |
| **heapq.heappush(arr, item)**    | Push a new item into the heap while retaining the heap structure                                                                                                     | O(log n)            |
| **heapq.heappop(arr)**           | Pop and return the **smallest item** from the heap                                                                                                                   | O(log n)            |
| **heapq.heappushpop(arr, item)** | Push and then pop in a single, more efficient operation                                                                                                              | O(log n)            |
| **heapq.nlargest(n, arr)**       | Retrieve the **n largest elements**                                                                                                                                  | O(n log n)          |
| **heapq.nsmallest(n, arr)**      | Retrieve the **n smallest elements**                                                                                                                                 | O(n log n)          |
---

## 🔹 How to Convert a Min-Heap to a Max-Heap in `heapq` 🔹

Python’s `heapq` is a **min-heap by default**.  
To convert it into a **max-heap**, we can use **negation**:

✅ **Negate the values before inserting into the heap.**  
(Inserting `-5` instead of `5`, for example).

✅ **Negate again after popping** to get back the **original (positive) values**.
