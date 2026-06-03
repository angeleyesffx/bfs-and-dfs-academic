# Breadth-First Search (BFS) and Depth-First Search (DFS) in C

### 🧮 Core Algorithms & Data Structures Portfolio

This repository contains a robust, pure C implementation of the classic **Graph Theory** traversal algorithms: **Breadth-First Search (BFS)** and **Depth-First Search (DFS)**. Designed with modular architectures, it adheres to the formal engineering standards outlined in Thomas H. Cormen's *"Introduction to Algorithms"*.

The project showcases advanced memory management, explicit pointer manipulation, dynamic queue/stack provisioning, and modular code encapsulation.

---

## 🚀 Architectural Design

The project is structured into independent, highly reusable components:
- `lista.c` / `lista.h`: Adjacency list representation for resource-efficient graph storage $O(V + E)$.
- `fila.c` / `fila.h`: Standard FIFO queue implementation specifically tuned to manage state transitions during **BFS** traversal.
- `main.c`: Core orchestration layer parsing graph vertices, executing discovery paths, and printing state color changes (WHITE, GRAY, BLACK).

### Algorithm Strengths:
- **BFS:** Implemented utilizing an explicit queue to compute shortest paths in unweighted graphs.
- **DFS:** Leverages recursive stack frames to discover deep topological structures, timestamps, and edge types.

---

## 🛠️ How to Compile and Run

This project includes a automated `Makefile` to streamline compilation and binary lifecycle management.

### Prerequisites
- GCC Compiler (`gcc`)
- GNU Make (`make`)

### Compiling
To compile the entire system and generate the optimized executable, simply run:
```bash
make
