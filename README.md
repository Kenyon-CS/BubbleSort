# BubbleSort
C++

## Explanation
1. bubbleSort Function:
  - The outer loop runs ```n-1``` times, where ```n``` is the number of elements. Each pass pushes the largest unsorted element to the end.
  - The inner loop compares adjacent elements. If an element is greater than the one after it, they are swapped.
  - The ```swapped``` flag is used to optimize the algorithm; if no elements are swapped in a pass, the array is already sorted, and the algorithm can exit early.
2. ```printArray``` Function: A helper function to print the array at any point.
