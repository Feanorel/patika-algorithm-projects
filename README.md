# patika-algorithm-projects
www.patika.dev
# Project 1
## [22,27,16,2,18,6] -> Insertion Sort

- [2,27,16,22,18,6] -> 2 to 22 swapping places.
- [2,6,16,22,18,27] -> 6 to 27 swapping places.
- [2,6,16,22,18,27] -> The 3rd row element is the smallest. No need to change.
- [2,6,16,18,22,27] -> 18 to 22 swapping places.
- [2,6,16,18,22,27] -> The 5th row element is the smallest. No need to change.
- [2,6,16,18,22,27] -> The 6th row element is the biggest and finish.

### Big-O 
-  O(n²) = O(6²) = O(36)

#### Time Complexity
- > **Average case: The number we are looking for is in the middle,** **<- Answer**
- > Worst case: The number we are looking for is at the end,
- > Best case: The number we are looking for is at the beginning of the array.

## [7,3,5,8,2,9,4,15,6] -> Insertion Sort
- [2,3,5,8,7,9,4,15,6] -> 7 to 2 swapping changes.
- [2,3,5,8,7,9,4,15,6] -> The 2nd row 3 is the smallest, no need to change.
- [2,3,4,8,7,9,5,15,6] -> 5 to 4 swapping changes.
- [2,3,4,5,7,9,8,15,6] -> 8 to 5 swapping changes.

# Project 2
## [16,21,11,8,12,22] -> Merge Sort

- Step 1: [16,21,11,8,12,22]
- Step 2: [16,21,11] - [8,12,22]
- Step 3: [16] - [21,11] - [8] - [12,22]
- Step 4: [16] - [21] - [11] - [8] - [12] - [22]
- Step 5: [16] - [21,11] - [8] - [12,22]
- Step 6  [11,16,21] - [8,12,22]
- Step 7: [8,11,12,16,21,22] 

### Big-O
- O(nlogn) = O(6log6)


