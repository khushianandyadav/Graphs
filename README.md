````markdown
# Graph Algorithms in Python 

This repository contains a Jupyter Notebook (`Graphs.ipynb`) that demonstrates fundamental graph representations and traversal algorithms using Python.

---

##  Contents
The notebook includes:
- Graph representation
  - Adjacency List
  - Adjacency Matrix
- Traversal algorithms
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS) – iterative & recursive
- Graph problem:
  - Cycle detection in an undirected graph

---

##  Getting Started

### Prerequisites
Make sure you have the following installed:
- Python 3.x
- Jupyter Notebook
- No external libraries are required (uses only core Python)

### Running the Notebook
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/graphs-algorithms.git
   cd graphs-algorithms
````

2. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open **Graphs.ipynb** and run the cells.

---

##  Example Output

* BFS traversal: `[0, 1, 3, 4, 2, 5]`
* DFS traversal (iterative): `[0, 4, 2, 5, 1, 3]`
* DFS traversal (recursive): `[0, 1, 2, 4, 3, 5]`
* Cycle detection: `True / False`
