# Sudoku Solver using CSP

This project implements a **Sudoku Solver** using a **CSP**.

The program takes a partially filled 9×9 Sudoku grid as input and fills it completely while satisfying all Sudoku rules.

---

## Problem Description

Given:
- A 9×9 Sudoku board
- Empty cells represented by `0`

Objective:
- Fill the board so that:
  - Each row contains digits 1–9 exactly once
  - Each column contains digits 1–9 exactly once
  - Each 3×3 subgrid contains digits 1–9 exactly once

---

## Input Format

- The user enters 9 rows
- Each row contains 9 integers separated by space
- Use `0` for empty cells

### Example Input
- Enter row 1
5 3 0 0 7 0 0 0 0
- Enter row 2
6 0 0 1 9 5 0 0 0
- Enter row 3
0 9 8 0 0 0 0 6 0
- Enter row 4
8 0 0 0 6 0 0 0 3
- Enter row 5
4 0 0 8 0 3 0 0 1
- Enter row 6
7 0 0 0 2 0 0 0 6
- Enter row 7
0 6 0 0 0 0 2 8 0
- Enter row 8
0 0 0 4 1 9 0 0 5
- Enter row 9
0 0 0 0 8 0 0 7 9
