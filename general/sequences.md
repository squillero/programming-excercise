# ARRAYS/SEQUENCES

## Add item in a specific position

Write a function that takes an *array*, a plausible element, and an index. The function should modify the array by adding the element in the specified position. Try to handle incorrect parameters.

```
INPUT: [1, 2, 3, 4, 5], 42, 3
OUTPUT: [1, 2, 3, 42, 4, 5]
```

## Add item in a specific position (take 2)

Write a function that takes an *array*, a plausible element, and an index. The function should modify the array by adding the element in the specified position, if the index is negative, it specifies the position from the last element. Try to handle incorrect parameters.

```
INPUT: [1, 2, 3, 4, 5], 42, -1
OUTPUT: [1, 2, 3, 4, 5, 42]
```

## Find pairs with given sum

Write a function that takes an *array* of integer and prints all the pairs of numbers that sum to *N*, with all possible *N*'s. Each number can appear in only one pair.

```
INPUT: [3, 1, 3, 2, 4, 1, 17, 1]
OUTPUT: 2:(1, 1) 3:(2, 1) 6:(3, 3) 21:(4, 17)
```

## Compare arrays

Checks if two *arrays*

1. Are identical, i.e., contains the same elements in the same order
1. Contains the same elements the same number of time, possibly in a different order. Note: [1, 2, 3, 2] does not match [1, 2, 3, 3].

## Subsequences

Given an array, find its longest subsequence repeated at least *N* times

```
INPUT: [3, 1, 2, 1, 2, 1, 3], N=2
OUTPUT: (1, 2, 1)
```

## Remove duplicates

Write a function for removing all duplicated elements from the array taken as input. If possible modify the array in-place, if not, returns the stripped array.

```
INPUT: [3, 1, 2, 1, 2, 4, 1, 3]
OUTPUT: [3, 1, 2, 4]
```
