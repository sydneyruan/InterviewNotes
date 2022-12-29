# Interview Notes
Common resources for Coding Interview, codes are in Python. I hope this can become a one-stop guide.
- [List, Dictionary, Set Time Complexity:](https://www.geeksforgeeks.org/complexity-cheat-sheet-for-python-operations/)
- Space Complexity
- [Python Bitwise Operators:](https://www.w3schools.com/python/python_operators.asp)

| Operator | Name | Description |
| ----------- | ----------- | ----------- |
| & | AND | Sets each bit to 1 if both bits are 1 |
| \| | OR | Sets each bit to 1 if one of two bits is 1 |
| ^ | XOR | Sets each bit to 1 if only one of two bits is 1 |
| ~ | NOT | Inverts all the bits |
| << | Zero fill left shift | Shift left by pushing zeros in from the right and let the leftmost bits fall off |
| >> | Signed right shift | Shift right by pushing copies of the leftmost bit in from the left, and let the rightmost bits fall off |

- Combination & Permutation

| Order? | Repetition? | Formula |
| ----------- | ----------- | ----------- |
| Yes | No | *P(n,r) =* $\frac{n!}{(n-r)!}$ |
| No | No | *C(n,r) =* $\frac{n!}{r!(n-r)!}$ |
| Yes | Yes | $n^r$ |
| No | Yes | *C(n+r-1,r) =* $\frac{(n+r-1)!}{r!(n-r)!}$ |

- Common Data Structures:
  - [Priority Queue](https://www.geeksforgeeks.org/priority-queue-in-python/)
  - [Deque](https://www.geeksforgeeks.org/deque-in-python/?ref=lbp)

- Common Coding Topics:
  - Binary Search
  - Stack, Queue & Heap
  - OOP
  - Sliding Window
  - Trees
  - Graphs
  - Dynamic Programming:
    - [Kadane’s Algo](https://medium.com/@rsinghal757/kadanes-algorithm-dynamic-programming-how-and-why-does-it-work-3fd8849ed73d)
      - [Best Time to Buy and Sell Stock (Easy)](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/solution/)
      - [Maximum Subarray (Medium)](https://leetcode.com/problems/maximum-subarray/)
  - List
  - DFS:
  - BFS:
  - Linked List:
  - Math Theory Related:
    - Linear Algebra: [Rotate Image](https://leetcode.com/problems/rotate-image/)
  - [Memoization](https://www.geeksforgeeks.org/python-functools-lru_cache/)
    - [Video Explanation](https://www.infoworld.com/article/3606188/speed-up-python-functions-with-memoization-and-lrucache.html)

- Common Technical Questions:
  - Sorting
    - [Merge Sort](https://www.geeksforgeeks.org/merge-sort/)
      - [Implementation](https://github.com/sydneyruan/interviews/blob/main/MergeSort.py)
      - Runtime: *O(nlog(n))*
    - [Quick Sort](https://www.geeksforgeeks.org/python-program-for-quicksort/)
      - [Implementation](https://github.com/sydneyruan/InterviewNotes/blob/main/QuickSort.py)
      - Runtime: *O(nlog(n))*


References:
- https://gist.github.com/TSiege/cbb0507082bb18ff7e4b
- https://algorithmicthinking.github.io/#/
