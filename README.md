# Sliding-Puzzle-Solver

A python program implementing any Search strategy to solve the arrange square puzzle (Image below).

![image](https://github.com/vedb1211/Sliding-Puzzle-Solver/assets/106091820/fe881d39-a747-4123-b2c1-787b8a64c5cb)

This is a Python program that solves a square puzzle using the Greedy Best First Search (GBFS) algorithm. The puzzle is represented as a grid of numbers where one cell is empty, and the goal is to reach a target configuration by sliding the numbered tiles into the empty cell.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)

## Introduction

This program uses object-oriented programming principles to represent the puzzle, nodes, and the search algorithm. The GBFS algorithm is used to search for the solution by considering the heuristic of the number of tiles out of place.

Heuristic used:
Number of Misplaced Tiles: This heuristic counts the number of tiles that are out of place in the current state compared to the goal state.
It considers the correctness of each tile's position independently.


## Features

- Solves square puzzles of different sizes.
- Visualizes the solved puzzle.
- Counts the number of explored states and steps taken to reach the solution.

## Prerequisites

- Python 3.x
- NumPy library





