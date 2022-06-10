# [Patika.dev](https://www.patika.dev) Data Structures and Algorithms Course

## Merge Sort Project

[16,21,11,8,12,22] -> Merge Sort

### Questions
1. Write the stages of the above array according to the sort type.
2. Write the Big-O notation.

### Answers

1. 

- The array will be splitted into binary part until only one element remains 
 - [16, 21, 11] --- [8, 12, 22]
 - [16] --- [21, 11] --- [8] --- [12, 22]
 - [16] --- [21] --- [11] --- [8] --- [12] --- [22]
- The concatenation process will start with the smallest numerical value
 - [16] --- [11, 21] --- [8] --- [12, 22]
 - [11, 16, 21] --- [8, 12, 22]
 - [8, 11, 12, 16, 21, 22]

2. 
- We are constantly dividing the array into 2 parts so, 2^x = n => logn,
- When combining, the cost of comparing elements with respect to each other is n - 1 => n,
- The cost of all these operations: O(n * logn)