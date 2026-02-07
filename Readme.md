# 🧠 DSA_Visualiser

DSA_Visualiser is a **desktop-based algorithm visualization tool** built using **C++ and the Qt framework**.  
The application is designed to help learners understand **Data Structures and Algorithms (DSA)** by providing **step-by-step visual animations** instead of static code-only explanations.

The project focuses on clarity, interactivity, and conceptual learning through a clean graphical interface.

---

## 🎯 Project Purpose

- To visually demonstrate how common algorithms work internally  
- To make abstract DSA concepts easier to understand  
- To gain hands-on experience with **Qt GUI development**, **C++**, and **CMake-based builds**  

This project serves both as a **learning aid** and a **practical systems-level GUI application**.

---

## 🧰 Tech Stack

- **Language:** C++  
- **Framework:** Qt (Qt Widgets)  
- **Build System:** CMake / qmake  
- **Platform:** Desktop (Windows / Linux / macOS)

---

## ✨ Features Overview

### 🔹 Sorting Algorithm Visualizations
The application provides animated visualizations for the following sorting algorithms:

- Bubble Sort  
- Selection Sort  
- Insertion Sort  
- Quick Sort  
- Merge Sort  

Each sorting module includes:
- Step-by-step animation of comparisons and swaps  
- Controls to **Start**, **Pause**, and **Reset** execution  
- Adjustable speed for animations  
- Array size selection (3–10 elements, limited for UI clarity)  

> Note: Input values are currently randomized and array size is limited due to screen constraints.

---

### 🔹 Backtracking Algorithms
Classic backtracking problems are visualized interactively:

#### Rat in a Maze
- Visual pathfinding from `(0,0)` to `(n-1,n-1)`  
- Customizable grid size (up to 9×9)  
- Interactive obstacle placement  
- Execution controls: Start, Pause, Reset  

#### N-Queens Problem
- Visual placement of queens on an `N × N` chessboard  
- Step-by-step backtracking visualization  
- Configurable board size (up to 9×9)  

These visualizations clearly illustrate recursive decision-making and backtracking.

---

### 🌳 Tree Data Structures
The tool includes visualization support for tree-based data structures:

#### Binary Search Tree (BST)
- Interactive insertion and deletion of nodes  
- Visualization of in-order traversal  

#### AVL Tree
- Self-balancing BST implementation  
- Visual rotations during insertions and deletions  
- Pause/Resume feature to observe balancing operations  

These modules help understand tree structure and balancing logic visually.

---

## ⚙️ Prerequisites

Before running the project, ensure you have:

- **Qt Framework** installed (Qt Creator recommended)  
- Basic familiarity with **CMake** or **qmake**  
- A C++ compiler compatible with Qt  

---

## 🛠️ Build & Run Instructions

### Option 1: Using Qt Creator (Recommended)
1. Open **Qt Creator**
2. Select **Open Project**
3. Choose `CMakeLists.txt`
4. Configure the Desktop Qt kit
5. Build and run the project

### Option 2: Using Terminal
```bash
mkdir build
cd build
cmake ..
make
./DSA_Visualiser
