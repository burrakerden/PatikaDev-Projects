# PatikaDev-Projects
## Data structures and algorithms

It contains "Selection Sort", "Merge Sort" and "Binary Search Tree" projects

## "SELECTION SORT"

## Insertion Sort

[22,27,16,2,18,6] -> Insertion Sort

Write the stages of the above sequence according to the sort type.

[22,27,16,2,18,6]

[16,22,27,2,18,6]

[2,16,22,27,18,6]

[2,6,16,22,27,18]

[2,6,16,18,22,27]



## Write the Big-O notation.

Worst Case: O(n^2)
Avarage Case: O(n^2)
Best Case: O(n)



Time Complexity: 

For which case does the number 18 apply after the array is sorted? Write.
After sorting the array, the number 18 is in the middle of the array, so the number 18 is covered by the Avarage Case.

Avarage Case: [2,6,16,18,22,27]

## Write the first 4 steps of the array according to the Selection Sort -> [7,3,5,8,2,9,4,15,6]

[2,3,5,8,7,9,4,15,6]

[2,3,4,8,7,9,5,15,6]

[2,3,4,5,7,8,9,15,6]

[2,3,4,5,6,8,9,15,7]


## "MERGE SORT"

[16,21,11,8,12,22] -> Merge Sort

## Write the stages of the above array according to the sort type.

[16,21,11] - [8,12,22]  STEP 1

[16,21] - [11] - [8,12] - [22]  STEP 2

[16] - [21] - [11] - [8] - [12] - [22]  STEP 3

[16,21] - [11] - [8,12] - [22]  STEP 4

[11,16,21] - [8,12,22]  STEP 5

[8,11,12,16,21,22]  STEP 6


## Write the Big-O notation.

O(nlogn)

## "BINARY SEARCH TREE"

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Write the Binary-Search-Tree stages of the array.


```
7
```
```
   7
  /
 5 
```
```
    7
   /
  5
 /
1 
```
```
    7
   / \
  5   8
 /
1 
```
```
    7
   / \
  5   8
 / 
1  
 \
  3
```
```
      7
     / \
    5   8
   / \
  1   6
 / \
0   3
```
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
```
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
```
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
```



[PatikaDev](www.patikadev.com)
