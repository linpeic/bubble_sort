# Bubble Sort

A simple implementation of the bubble sort algorithm in Python.

## What is Bubble Sort?

Bubble sort is a basic sorting algorithm that repeatedly steps through a list, compares adjacent elements, and swaps them if they are in the wrong order. The pass through the list is repeated until no swaps are needed, which indicates the list is sorted.

## How it Works

1. Start at the beginning of the list
2. Compare the first two elements
3. If the first element is greater than the second, swap them
4. Move to the next pair of adjacent elements and repeat
5. Continue until the end of the list is reached
6. Repeat the entire process until no swaps are needed

## Time Complexity

- **Best case:** O(n) — when the list is already sorted
- **Average case:** O(n²)
- **Worst case:** O(n²)

## Usage

Run the program:

```bash
python bubble_sort/bubble\ sort.py
```

Output:
```
Original array: [64, 34, 25, 12, 22, 11, 90]
Sorted array: [11, 12, 22, 25, 34, 64, 90]
```
