# Array Challenge – Binary Tree Validation

## Problem Description
Given an array of strings containing integer pairs in `(child, parent)` format, determine whether the pairs can form a valid binary tree.

A valid binary tree must satisfy:
- Each node can have a maximum of two children.
- Each child must have only one parent.
- The tree must have exactly one root node.
- The tree must not contain cycles or disconnected nodes.

Return `"true"` if a valid binary tree can be formed; otherwise, return `"false"`.

## Example 1
**Input:**
```python
["(1,2)", "(2,4)", "(7,2)"]
```
**Output:** `true`

## Example 2
**Input:**
```python
["(1,2)", "(3,2)", "(2,12)", "(5,2)"]
```
**Output:** `false`

## Concepts Used
Python, Arrays, Dictionaries, Sets, Binary Trees, DFS, Recursion.

**Language:** Python 3  
**Difficulty:** Intermediate