# NON LANGUAGE SPECIFIC PROBLEMS

## NUMERIC

### N1. Greatest Common Divisor (GCD)

Write a function that calculates the Greatest Common Divisor of its parameters.

### N2. Prime numbers

Write a function that checks if its argument is prime.

### N3. Mersenne primes

A Mersenne prime is a prime number that is one less than a power of two. That is, it is a prime number of the form $$M_n = 2^n − 1$$ for some integer exponent *n*.

Determine the first 7 exponent $n$ and the resulting Mersenne primes.

> Answer: (2, 3, 5, 7, 13, 17, 19) and (3, 7, 31, 127, 8,191, 131,071, 524,287)

### N4. Prime numbers (takes 2)

Write a function that checks if its argument is prime and it can be expressed as sum of two prime numbers.

### N5. Armstrong numbers

An Armstrong number of *N* digits is an integer such that the sum of its digits to the power of *N* is equal to the number itself. For example, 9,474 is an Armstrong number: $$9^4 + 4^4 + 7^4 + 4^4 = 9,474$$

Write a program to find the largest Armstrong number below one million.

> Answer: 548,834

## ARRAYS/SEQUENCES

### Add item in a specific position

Write a function that takes an *array*, a plausible element, and an index. The function should modify the array by adding the element in the specified position. Try to handle incorrect parameters.

```
INPUT: [1, 2, 3, 4, 5], 42, 3
OUTPUT: [1, 2, 3, 42, 4, 5]
```

### Add item in a specific position (take 2)

Write a function that takes an *array*, a plausible element, and an index. The function should modify the array by adding the element in the specified position, if the index is negative, it specifies the position from the last element. Try to handle incorrect parameters.

```
INPUT: [1, 2, 3, 4, 5], 42, -1
OUTPUT: [1, 2, 3, 4, 5, 42]
```

### Find pairs with given sum

Write a function that takes an *array* of integer and prints all the pairs of numbers that sum to *N*, with all possible *N*'s. Each number can appear in only one pair.

```
INPUT: [3, 1, 3, 2, 4, 1, 17, 1]
OUTPUT: 2:(1, 1) 3:(2, 1) 6:(3, 3) 21:(4, 17)
```

### Compare arrays

Checks if two *arrays*

1. Are identical, i.e., contains the same elements in the same order
1. Contains the same elements the same number of time, possibly in a different order. Note: [1, 2, 3, 2] does not match [1, 2, 3, 3].

### Subsequences

Given an array, find its longest subsequence repeated at least *N* times

```
INPUT: [3, 1, 2, 1, 2, 1, 3], N=2
OUTPUT: (1, 2, 1)
```

### Remove duplicates

Write a function for removing all duplicated elements from the array taken as input. If possible modify the array in-place, if not, returns the stripped array.

```
INPUT: [3, 1, 2, 1, 2, 4, 1, 3]
OUTPUT: [3, 1, 2, 4]
```
