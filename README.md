# HackerRank 3rd Sem Algorithm Portfolio

## Student Information

- **Name:** Hari Priya E
- **USN / Student ID:** R25EF096
- **Semester:** 3rd Semester

## HackerRank Profile

https://www.hackerrank.com/profile/haripriyae27

## GitHub Repository

https://github.com/Haripriya994/HackerRank-3rdSem-Algorithm-Portfolio

## Introduction

This portfolio contains five algorithmic problem solutions developed as part of the HackerRank Algorithms & GitHub Coding Portfolio assignment. The solutions cover arrays, sorting, searching, and greedy algorithms.

## Problems

### 1. Mini-Max Sum

**Approach:**  
[The algorithm calculates the total sum of all elements while tracking the minimum and maximum values. The minimum sum is obtained by subtracting the maximum value from the total, and the maximum sum is obtained by subtracting the minimum value.]

**Time Complexity:** O(N)

**Auxiliary Space Complexity:** O(1)

### 2. Birthday Cake Candles

**Approach:**  
[The algorithm scans the candle heights once while keeping track of the tallest candle and how many candles have that height. Whenever a new maximum is found, the count is reset; when the same maximum is found, the count is increased.]

**Time Complexity:** O(N)

**Auxiliary Space Complexity:** O(1)

### 3. Insertion Sort – Part 1

**Approach:**  
[The last element is treated as the value to insert. Elements larger than this value are shifted one position to the right until the correct position is found, and then the value is inserted.]

**Time Complexity:** O(N)

**Auxiliary Space Complexity:** O(1)
### 4. Binary Search

**Approach:**  
[The algorithm searches a sorted array by repeatedly checking the middle element. If the target is equal to the middle element, its position is returned. If the target is smaller, the search continues in the left half; otherwise, it continues in the right half.]

**Time Complexity:** O(log N)

**Auxiliary Space Complexity:** O(1)

### 5. Mark and Toys

**Approach:**  
[The prices are sorted in ascending order. Starting with the cheapest toy, the algorithm keeps buying toys while the total cost remains within the available budget.]

**Time Complexity:** O(N log N)

**Auxiliary Space Complexity:** O(1)

## Summary

| Problem | Technique | Time Complexity | Space Complexity |
|---|---|---|---|
| Mini-Max Sum | Min/Max Tracking | O(N) | O(1) |
| Birthday Cake Candles | Counting | O(N) | O(1) |
| Insertion Sort – Part 1 | Insertion/Sorting  | O(N)| O(1) |
| Binary Search | Divide and Conquer | O(log N) | O(1) |
| Mark and Toys | Greedy + Sorting | O(N log N) | O(1) |
## Alternative Approaches

### Mini-Max Sum
An alternative approach is to sort the array and calculate the sum of all elements except the first element for the maximum sum and except the last element for the minimum sum.

### Birthday Cake Candles
An alternative approach is to first find the maximum candle height and then make a second pass through the array to count how many candles have that height.

### Insertion Sort – Part 1
An alternative approach is to use a general insertion sort implementation that processes the complete array rather than inserting only the final element.

### Binary Search
An alternative approach is linear search, which checks each element sequentially. However, binary search is more efficient for a sorted array.

### Mark and Toys
An alternative approach is to use a different sorting method before selecting the cheapest toys, depending on the available implementation and constraints.

## HackerRank Challenge Links
1. [Mini-Max Sum](https://www.hackerrank.com/challenges/mini-max-sum/problem)
2. [Birthday Cake Candles](https://www.hackerrank.com/challenges/birthday-cake-candles/problem)
3. [Insertion Sort – Part 1](https://www.hackerrank.com/challenges/insertionsort1/problem)
4. Binary Search — implemented in C in VS Code as permitted by the assignment.
5. [Mark and Toys](https://www.hackerrank.com/challenges/mark-and-toys/problem)

## Evidence

### 1. Mini-Max Sum
Accepted submission completed on HackerRank.

### 2. Birthday Cake Candles
Accepted submission completed on HackerRank.

### 3. Insertion Sort – Part 1
Accepted submission completed on HackerRank.

### 4. Binary Search
Implemented and tested successfully in C using VS Code.

### 5. Mark and Toys
Accepted submission completed on HackerRank.

## Badge Evidence

HackerRank badge evidence will be added here if earned.
