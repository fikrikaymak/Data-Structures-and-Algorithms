Project 3

*Write the Binary-Search-Tree stages of the sequence* 
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2].

Example: root is x. y is found to the right of root. To its left is a z, etc.

**Regular Binary Search Tree**
1. Insert 7 also root is 7
```
[7]
```
2. Insert 5
```
  [7]
 /
[5] 
```
3. Insert 1
```
      [7]
     /
   [5]
   /
[1] 
```
4. Insert 8
```
      [7]
     /   \
   [5]   [8]
  /
[1] 
```
5. Insert 3
```
      [7]
     /   \
   [5]   [8]
   /
[1] 
   \
   [3]
```
6. Insert 6
```
      [7]
     /   \
   [5]   [8]
  /   \
[1]   [6]
   \
   [3]
```
7. Insert 0
```
         [7]
        /   \
      [5]   [8]
     /   \
   [1]   [6]
  /   \
[0]   [3]
```
8. Insert 9
```
         [7]
        /   \
      [5]    [8]
     /   \      \
   [1]   [6]     [9]
  /   \
[0]   [3]
```
9. Insert 4
```
         [7]
        /   \
      [5]    [8]
     /   \      \
   [1]   [6]     [9]
  /   \
[0]   [3]
         \
          [4]

```
10. Insert 2
```
          [7]
         /   \
      [5]     [8]
     /   \       \
   [1]    [6]     [9]
  /   \
[0]    [3]
      /   \
    [2]    [4]
```

Root is 7
[5,1,6,0,3,2,4] is located to on the left the root
[8,9] is located to on the right the root



**If choose the root as 6**
           [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

                        [6]
                       /   \
                     [5]   [7]
                    /         \
                  [1]         [8]
                 /   \           \
               [0]   [3]         [9]  
                     /  \
                   [2]   [4]
```

*Root is 6,
[5,1,0,3,2,4] is located to on the left the root.
[7,8,9] is located to right on the root.*