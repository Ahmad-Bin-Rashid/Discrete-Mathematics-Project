# Discrete Mathematics Project

A comprehensive implementation of **Graph Theory** and **Number Theory** algorithms from a first-semester Discrete Mathematics course. This project demonstrates practical applications of core mathematical concepts through C++ implementations.

## 📋 Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Graph Theory Tasks](#graph-theory-tasks)
- [Number Theory Tasks](#number-theory-tasks)
- [Getting Started](#getting-started)
- [Technologies](#technologies)
- [Course Information](#course-information)
- [Detailed Specifications](#detailed-specifications)

## Overview

This project explores fundamental concepts in discrete mathematics with a focus on computational implementations:

- **Graph Theory**: Representation, analysis, and properties of various graph types
- **Number Theory**: Cryptographic algorithms, number operations, and mathematical computations

Each task is solved with efficient C++ implementations, demonstrating algorithm design and problem-solving techniques.

## Project Structure

```
Discrete-Mathematics-Project/
├── Graph Theory Tasks/          # 6 tasks on graph algorithms and analysis
│   ├── task1.cpp               # Game representation using graph theory
│   ├── task2.cpp               # Tic-Tac-Toe analysis
│   ├── task3.cpp               # Undirected graph vertex degrees
│   ├── task4.cpp               # Directed graph in-degree and out-degree
│   ├── task4-version2.cpp      # Alternative implementation
│   ├── task5.cpp               # Bipartite graph detection
│   ├── task6.cpp               # Adjacency matrix construction
│   └── ScreenShots/            # Demonstration screenshots
│
├── Number Theory Tasks/         # 7 tasks on number theory operations
│   ├── task1.cpp               # Prime factorization
│   ├── task2.cpp               # Euclidean algorithm for GCD
│   ├── task3.cpp               # LCM calculation
│   ├── task4.cpp               # Bezout coefficients
│   ├── task5.cpp               # Modular inverse
│   ├── task6.cpp               # RSA encryption
│   ├── task7.cpp               # RSA decryption key
│   └── ScreenShots/            # Demonstration screenshots
│
├── README.md                    # Project documentation
└── TASKS.md                     # Detailed task specifications
```

## Graph Theory Tasks

| Task | Description |
|------|-------------|
| **Task 1** | Game representation using graph theory (multiple game analysis) |
| **Task 2** | Tic-Tac-Toe graph representation with generalizations |
| **Task 3** | Calculate vertex degrees in undirected graphs |
| **Task 4** | Compute in-degree and out-degree for directed graphs |
| **Task 5** | Detect whether a graph is bipartite |
| **Task 6** | Generate adjacency matrices (with support for loops, multiple edges, and directed edges) |

## Number Theory Tasks

| Task | Description |
|------|-------------|
| **Task 1** | Prime factorization of positive integers |
| **Task 2** | GCD calculation using Euclidean algorithm |
| **Task 3** | LCM calculation for two integers |
| **Task 4** | Calculate Bezout coefficients for linear Diophantine equations |
| **Task 5** | Modular inverse computation for relatively prime integers |
| **Task 6** | RSA message encryption |
| **Task 7** | RSA decryption key calculation |

## Getting Started

### Prerequisites
- C++ compiler (g++, clang, or MSVC)
- Standard C++ library

### Compilation and Execution

To compile and run any task:

```bash
# Graph Theory Tasks
g++ Graph\ Theory\ Tasks/taskX.cpp -o taskX
./taskX

# Number Theory Tasks
g++ Number\ Theory\ Tasks/taskX.cpp -o taskX
./taskX
```

Replace `X` with the task number (1-6 for graph theory, 1-7 for number theory).

## Technologies

- **Language**: C++
- **Paradigm**: Procedural Programming
- **Standard**: C++11 or later
- **Compilation**: Command-line compilation with standard C++ compiler

## Algorithms & Concepts Covered

### Graph Theory
- Graph representation (adjacency matrix, edge lists)
- Vertex degree calculations
- Bipartite graph detection (Graph coloring)
- Incidence matrix construction

### Number Theory
- Prime factorization algorithms
- Euclidean algorithm for GCD
- Extended Euclidean algorithm (Bezout coefficients)
- Modular arithmetic
- RSA cryptosystem implementation

## Course Information

**Course**: Discrete Mathematics (1st Semester)  
**Instructor**: [Waqas Ali](https://www.linkedin.com/in/waqas-ali-429922261/)  


## Detailed Specifications

For comprehensive task specifications, requirements, algorithms, and implementation notes, see [TASKS.md](TASKS.md).

---

## Notes

- Each task includes well-commented C++ code for clarity
- Screenshots of execution and outputs are included in respective folders
- Complete task requirements with examples are documented in TASKS.md

## License

This project is created for educational purposes as part of a Discrete Mathematics course.

