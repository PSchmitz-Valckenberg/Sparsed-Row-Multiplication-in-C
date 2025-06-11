# Sparse Row Matrix Multiplication in C (CSR Format)

This project implements an optimized multiplication of two sparse matrices using the **Compressed Sparse Row (CSR)** format.  
It is written in **C** for maximum performance and control over memory layout and operations.

## 🧠 Why Sparse Matrices?

Sparse matrices (also called *dünnbesetzte Matrizen*) are matrices in which most of the elements are zero.  
Storing and computing them efficiently requires specialized data structures like CSR to avoid unnecessary memory usage and operations.

## ⚙️ Features

- Efficient representation of sparse matrices in **CSR format**
- Optimized multiplication logic with loop unrolling and index skipping
- Memory-safe implementation with proper dynamic allocation
- Simple CLI structure for input and benchmarking


