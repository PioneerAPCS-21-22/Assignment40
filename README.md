# Assignment 40

For this assignment you will be writing two recursive methods. The methods can be in one class with your `main` method. Put each of the six tests below in your `main` method.

## Part 1

Given a non-negative int n, return the sum of its digits recursively (no loops).
Note that mod (%) by 10 yields the rightmost digit (126 % 10 is 6),
while divide (/) by 10 removes the rightmost digit (126 / 10 is 12).

### Sample Outputs
```
sumDigits(126) → 9
sumDigits(49) → 13
sumDigits(12) → 3
```

## Part 2

Given a triangle made of blocks, the topmost row has 1 block, the next row down has 2 blocks, the next row has 3 blocks, and so on.
Compute recursively (no loops or multiplication) the total number of blocks in such a triangle with the given number of rows.

### Sample Outputs
```
triangle(0) → 0
triangle(1) → 1
triangle(2) → 3
triangle(5) → 15
```

## Challenge \#1

Given a string, compute recursively (no loops) a new string where all appearances of "pi" have been replaced by "3.14".

### Sample Outputs
```
changePi("xpix") → "x3.14x"
changePi("pipi") → "3.143.14"
changePi("pip") → "3.14p"
```

## Challenge \#2

The Fibonacci numbers start with 1 as the term at 0 and 1. You then get the next term by adding the two previous terms together. The list is below.

| 0   | 1   | 2   | 3   | 4   | 5   | 6   | ... |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1   | 1   | 2   | 3   | 5   | 8   | 13  | ... |

Given an integer n, give the nth Fibonacci number.

### Sample Outputs
```
fibonacci(0) → 1
fibonacci(3) → 3
fibonacci(6) → 13
```

### Grading

Please make sure you have comments for every method you create. As always, your program will be graded on its functionality according to the project specifications and proper code style.

