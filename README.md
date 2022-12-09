# Interview Notes
Coding Interview Prep, codes are in Python
- List, Dictionary, Set Time Complexity: https://www.geeksforgeeks.org/complexity-cheat-sheet-for-python-operations/
- Space Complexity
- Python Bitwise Operators: https://www.w3schools.com/python/python_operators.asp

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
| Yes | No | P(n,r) = $\frac{n!}{(n-r)!}$ |
| No | No | C(n,r) = $\frac{n!}{r!(n-r)!}$ |
| Yes | Yes | $n^r$ |
| No | Yes | C(n+r-1,r) = $\frac{n+r-1)!}{r!(n-r)!}$ |


- Common Coding Topics:
  - [ ] Dynamic Programming:
        - [ ] Maximum Subarray: https://leetcode.com/problems/maximum-subarray/
        - Kadane’s Algo: https://medium.com/@rsinghal757/kadanes-algorithm-dynamic-programming-how-and-why-does-it-work-3fd8849ed73d
  - [ ] List

- Common Technical Questions:
  - Sorting
        - Merge Sort:
          - Runtime: O(nlogn)
          - Implementation:
          - ''def mergeSort(arr):
    if len(arr) > 1:
 
        # Finding the mid of the array
        mid = len(arr)//2
        # Dividing the array elements
        L = arr[:mid]
        # into 2 halves
        R = arr[mid:]
        # Sorting the first half
        mergeSort(L)
        # Sorting the second half
        mergeSort(R)
 
        i = j = k = 0
 
        # Copy data to temp arrays L[] and R[]
        while i < len(L) and j < len(R):
            if L[i] <= R[j]:
                arr[k] = L[i]
                i += 1
            else:
                arr[k] = R[j]
                j += 1
            k += 1
        # Checking if any element was left
        while i < len(L):
            arr[k] = L[i]
            i += 1
            k += 1
        while j < len(R):
            arr[k] = R[j]
            j += 1
            k += 1
            ''
