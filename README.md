# CSP_Sudoko_Solver_
Added Sudoku CSP solver with backtracking and forward checking
# 🧠 Sudoku Solver using CSP (AI Assignment)

## 📌 Description

This project is a Sudoku Solver built using **Constraint Satisfaction Problem (CSP)** techniques.
It solves Sudoku puzzles using **Backtracking Search, Forward Checking, and AC-3 (basic)**.

The solver can handle different difficulty levels like **easy** and **medium**, and shows performance using backtracking statistics.

---

## 🎯 Objective

The goal of this project is to:

* Apply CSP concepts to a real problem
* Solve Sudoku using AI techniques
* Understand backtracking and constraint propagation

---

## ⚙️ Approach

### ✔ CSP Formulation

* **Variables:** Empty cells in Sudoku
* **Domain:** Values from 1 to 9
* **Constraints:**

  * No repetition in rows
  * No repetition in columns
  * No repetition in 3×3 grid

---

### ✔ Algorithms Used

* **Backtracking Search (DFS)** → main solving method
* **Forward Checking** → check before placing value
* **AC-3 (basic)** → included for constraint propagation idea

---

## 🧪 Input Format

* 9×9 Sudoku board
* 0 represents empty cells

Example:

```
004030050
609400000
005100489
000060930
300807002
026040000
453009600
000004705
090050200
```

---

## 🚀 How to Run (Jupyter Notebook)

1. Open Jupyter Notebook
2. Copy the code into a cell
3. Run the cell

Change difficulty here:

```python
run_sudoku("easy")
# run_sudoku("medium")
```

---

## 📊 Output

* Solved Sudoku board
* Number of backtracking calls
* Number of failures

---

## 📁 Project Structure

```
sudoku-csp/
│── sudoku_solver.ipynb
│── README.md
```

---

## 💡 Results

The solver successfully solves:

* Easy Sudoku
* Medium Sudoku

It also tracks performance using backtracking metrics.

---

## 📝 Notes

* Code is written in simple Python
* Comments are kept minimal and easy to understand
* Designed for learning CSP concepts

---

## 🔗 Author

Ali Hassan FAST NUCES CFD CAMPUS 
