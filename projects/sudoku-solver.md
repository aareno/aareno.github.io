---
layout: project
type: project
image: img/sudokuclip2.png
title: "Sudoku Solver"
date: 2021
published: true
labels:
  - Java
  - ICS211
summary: "A program that can solve any sudoku problem."
---

This project is a program that can solve any sudoku problem. I made this project in my 2nd year at UH Manoa, in ICS211. Through this project I learned more about looping through two dimensional arrays and using recursion. I really enjoyed this project because it was fun to see that the program could solve any sudoku problem.

## What is sudoku?

A 9x9 square must be filled with numbers 1-9 with no repeating numbers in each line, horizontally, vertically and in the same 3 x 3.

## How it works

This program works by looping through the rows and column of the sudoku problem. Whenever there is a empty cell in the sudoku problem, a function to get the possible values were called. Each possible value is tested by checking if the same number is in the same row, column or 3 x 3, if all of these conditions are satisfied, the number is plotted. This process is repeated until the sudoku is solved.

This is an example of my program solving a sudoku problem:

<img class="resize" src="../img/sudoku-solver.png" style="width:400px; height:300px">
