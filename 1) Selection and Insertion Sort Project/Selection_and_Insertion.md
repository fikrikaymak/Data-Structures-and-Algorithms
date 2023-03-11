[22,27,16,2,18,6] -> Insertion Sort
Write the steps of the above given sequence according to the sort type.
1.  [22,27,16,2,18,6]
2.  [22,27,16,2,18,6]
3.  [16,22,27,2,18,6]
4.  [2,16,22,27,18,6]
5.  [2,16,18,22,27,6]
6.  [2,6,16,18,22,27]

 Write the **Big-O** notation

*`1+...+(n-2)+(n-1)+n` `=` `n*(n+1)/2 `*

*n^2^+n/2*


**O** ***(n^2^)***

---
*Time Completixy: After the array is sorted, which of the following cases falls under the number 18? Write it down.*
1. Average Case: The number we are looking for is in the middle
2. Worst case: The number we are looking for is at the end
3. Best case: The number we're looking for is at the top of the index

**Answer:** Average Case

---


[7,3,5,8,2,9,4,15,6] 

*Write the first 4 steps of the sequence according to the Selection Sort.*

Steps:
1.  [2,3,5,8,7,9,4,15,6]
2.  [2,3,5,8,7,9,4,15,6]
3.  [2,3,4,8,7,9,5,15,6]
4.  **[2,3,4,5,7,9,8,15,6]**
5.  [2,3,4,5,6,9,8,15,7]
6.  [2,3,4,5,6,7,8,15,9]
7.  [2,3,4,5,6,7,8,15,9]
8.  [2,3,4,5,6,7,8,9,15]

**O(n^2^)**