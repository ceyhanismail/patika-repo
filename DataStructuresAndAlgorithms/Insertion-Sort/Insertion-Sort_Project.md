# [Patika.dev](https://www.patika.dev) Data Structures and Algorithms Course

## Insertion Sort Project

[22,27,16,2,18,6] -> Insertion Sort

### Questions;

1. Write the steps of sorting the array above
2. Write the Big-O notation.
3. Time Complexity: 
- Average case: The number we are looking for is in the middle.
- Worst case: The number we are looking for is at the end. 
- Best case: The number we are looking for is at the beginning of the series.
4. What case does the number 18 fall into after the array is sorted?

5. Write the first 4 steps of [7,3,5,8,2,9,4,15.6] according to Insertion Sort.

### Answers;

1. Insertion sort steps:
- [22,27,16,2,18,6]  (n)
- [2,27,16,22,18,6]  (n-1)
- [2,6,16,22,18,27]  (n-2)
- [2,6,16,18,22,27]  (n-3)
- [2,6,16,18,22,27]  (n-4)
- [2,6,16,18,22,27]  (1)

2. Sum of the numbers from 1 to n = [n.(n-1)/2] = [n^2-n]/2. Therefore, the Big-O notation is O(n^2)

3. Time Complexity: 
- Average case: The number we are looking for is in the middle. ---> n
- Worst case: The number we are looking for is at the end. ---> n^2
- Best case: The number we are looking for is at the beginning of the series. ---> n^2

4. The case would be average case since the number 18 would be in the middle after the array is sorted.

5. 
- [7,3,5,8,2,9,4,15.6]

- [3,7,5,8,2,9,4,15,6]
- [3,5,7,8,2,9,4,15,6]
- [3,5,7,8,2,9,4,15,6]
- [2,3,5,7,8,9,4,15,6]