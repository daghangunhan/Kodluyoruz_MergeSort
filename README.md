# Exercise for Merge Sort Algorithm

### Question:

Write the steps of the **[16,21,11,8,12,22]** array according to the Merge Sort.
Write the Big-O notation.

### Answer:

Steps of the Merge Sort are given in the Figure below.

![Merge](https://raw.githubusercontent.com/daghangunhan/Kodluyoruz_MergeSort/main/visuals/Merge.JPG)

**Big-O Notation:**

The number of operations is (n-1) at the each stage of combining arrays.
The number of times to combine arrays is calculated as follows.

2^x=n 
x=log_2(n)

Total number of operations: (n-1)*log_2(n)

Big-O notation: O(n*logn)
