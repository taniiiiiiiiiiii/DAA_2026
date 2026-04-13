# Quick Sort Implementation in C

## Description

This project implements the Quick Sort algorithm using the Hoare Partition technique in C. It demonstrates efficient sorting using a divide-and-conquer approach.

## Features

* Implementation using Hoare Partition
* Efficient sorting (O(n log n) average case)
* User input supported
* Simple and clean code

## Technologies Used

* C Programming Language
* Standard Library (stdio.h)

## Project Structure

```
project-folder/
│── quicksort.c
│── README.md
```

## How to Run

### Compile

```
gcc quicksort.c -o quicksort
```

### Run

```
./quicksort
```

## Sample Input

```
Enter number of elements:
5
Enter elements:
5 3 8 1 2
```

## Sample Output

```
Before sorting:
5 3 8 1 2

Sorted array:
1 2 3 5 8
```

## Algorithm

### Quick Sort (Hoare Partition)

1. Choose the first element as pivot
2. Initialize two pointers (i and j)
3. Move i to the right until element >= pivot
4. Move j to the left until element <= pivot
5. Swap elements if i < j
6. Repeat until i >= j
7. Recursively sort subarrays

## Pseudocode

```
QUICKSORT(A, l, r)
  if l < r
    s = PARTITION(A, l, r)
    QUICKSORT(A, l, s)
    QUICKSORT(A, s+1, r)
```

## Time Complexity

* Best Case: O(n log n)
* Average Case: O(n log n)
* Worst Case: O(n^2)

## Space Complexity

* O(log n)

## Advantages

* Faster than simple sorting algorithms
* In-place sorting
* Efficient for large datasets

## Limitations

* Worst case for already sorted data
* Recursive calls use stack space

## Author

Tanisha Suhas Rao

## Contribution

Feel free to fork and improve this project.

## Support

Give this project a star if you like it.
