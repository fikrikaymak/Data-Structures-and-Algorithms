[16,21,11,8,12,22] -> Merge Sort


* *Write the stages of the above array according to the sort type.*

**Solution:**
```
           [16,21,11,8,12,22]
     [16,21,11]           [8,12,22]
  [16,21]   [11]        [8,12]    [22]
[16] [21]    [11]     [8] [12]     [22]
 [16, 21]   [11]       [8,12]     [22]
     [11,16,21]           [8,12,22]
           [8,11,12,16,21,22]
```

* *Write the Big-O notation.*

2^x^ = n
x = logn
x*n= Big-O notation
**O(nlogn)**
