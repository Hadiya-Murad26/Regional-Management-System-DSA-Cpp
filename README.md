# Regional-Management-System-DSA-Cpp
The provided code snippet implements various data structures and algorithms to manage and analyze data related to countries and cities. Here's a high-level breakdown of its components:

### **1. Doubly Linked List**
- The `Node` structure represents a country's data (name, population, income, and annual rainfall).
- Functions like `addNode` and `printAll` manage and display the linked list's content.

### **2. Binary Search Tree (BST)**
- The `TreeNode` structure represents nodes in the BST, with data similar to the `Node` structure.
- Functions like `addToTree2` and `displayTree` allow adding nodes to the BST based on population and display the tree in sorted order.

### **3. Max Heap**
- The `MaxHeap` class is implemented to manage nodes based on their rainfall in descending order.
- Supports operations like `insert`, `deleteMax`, and `heapSort`.

### **4. Graph Representation**
- Graph data is dynamically created from a CSV file using a 2D array.
- Functions like `readCSV` and `createGraph` handle CSV parsing and graph creation.
- Graph data is printed using `printGraph`.

### **5. Graph Algorithms**
- **Dijkstra's Algorithm:** Calculates the shortest path from a starting city to all other cities.
- **Prim's Algorithm:** Computes the Minimum Spanning Tree (MST) starting from a given city.

### **6. Utility Functions**
- `sortUsingHeap` sorts the linked list nodes using a MaxHeap based on rainfall.
- `readCSV` and `createGraph` load and prepare data for graph-related operations.


