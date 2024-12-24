# get_next_line

[![42 École](https://img.shields.io/badge/42-École-000000?style=flat&logo=42&logoColor=white)](https://42.fr)

The `get_next_line` project focuses on creating a function that reads a file line by line, including the newline character. It is a key project in the 42 École curriculum designed to deepen understanding of file descriptors, memory management, and efficient file handling in C.

---

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Function Prototype](#function-prototype)
- [Installation](#installation)

---

## About the Project

The goal of the `get_next_line` project is to create a function that reads a file descriptor one line at a time, returning each line including its newline character (if present). This project focuses on:

- Managing static and dynamic memory allocation.
- Handling multiple file descriptors simultaneously.
- Optimizing performance by using a buffer.

---

## Features

- Reads files line by line, returning each line including the newline character.
- Handles multiple file descriptors concurrently.
- Optimized for memory management, preventing leaks and overflows.
- Compatible with any buffer size.

---

## Function Prototype

```c
char *get_next_line(int fd);
```
---
## Installation:
1. Clone the repository:
   ```bash
   git clone
   ```
2. Enter the folder:
   ```bash
   cd GNL
   ```
3. Compile:
   ```bash
   make
   ```
