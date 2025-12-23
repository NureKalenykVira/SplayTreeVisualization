# Splay Tree Visualization

Educational web application for visualizing the Splay Tree data structure and its self-adjusting behavior.
The project demonstrates how splay operations reorganize the tree after each access, improving average access time.

---

## Tech Stack

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000000)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## About the Project

This project provides an interactive visualization of the Splay Tree data structure.
It allows users to observe how the tree restructures itself through rotations after search, insertion, and deletion operations.

The visualization is intended for educational purposes and helps to better understand self-adjusting binary search trees.

---

## Data Structure Overview

A splay tree is a self-adjusting binary search tree that performs a splay operation after each access.

Key concepts demonstrated:
- binary search tree properties
- splay operations (zig, zig-zig, zig-zag)
- tree rotations
- amortized efficiency of operations

The accessed node is moved to the root, improving performance for frequently accessed elements.

---

## Functional Overview

Application features:
- visual representation of tree nodes and edges
- insertion of new values into the tree
- search operations with automatic splaying
- deletion of nodes
- animated rotations during splay operations

Each operation updates the visualization to reflect the current tree structure.

---

## Application Structure

    SplayTreeVisualization/
      index.html          # main HTML file
      style.css           # styles for visualization
      script.js           # splay tree logic and visualization
      README.md

---

## Getting Started

To run the application locally:

    1. clone the repository
    2. open index.html in a browser

No additional dependencies or build steps are required.

---

## Educational Use

This project can be used as:
- a learning aid for data structures courses
- a visual explanation of self-adjusting trees
- a demonstration of tree rotations and amortized analysis concepts

---

## Project Status

Core visualization and splay tree operations are implemented.

Possible future improvements:
- step-by-step execution controls
- animation speed adjustment
- support for larger trees
- comparison with other balanced tree structures
