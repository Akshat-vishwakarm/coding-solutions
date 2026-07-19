# A Very Big Sum

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

Given a square matrix, calculate the absolute difference between the sums of its diagonals.  
  
For example, the square matrix $arr$ is shown below:  

	1 2 3
    4 5 6
    9 8 9  
    
- The left-to-right diagonal = $1 + 5 + 9 = 15$.    
- The right-to-left diagonal = $3 + 5 + 9 = 17$.    

Their absolute difference is $|15 - 17| = 2$.  

**Function description**

Complete the $\textit{diagonalDifference}$ function with the following parameter:  
  
-	$int\ arr[n][m]$: a 2-D array of integers 
    
**Return**  

-	$int$: the absolute difference in sums along the diagonals	

**Input Format**

The first line contains a single integer, $n$,  the number of rows and columns in the square matrix $arr$.  
Each of the next $n$ lines describes a row, $arr[i]$, and consists of $n$ space-separated integers $arr[i][j]$.

**Constraints**

+ $-100 \le arr[i][j] \le 100$

**Output Format**

## Solution

**Language:** Python  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-07-19T18:50:59.489Z  

```py
lent = int(input())

arr = list(map(int, input().split()))

sum = 0
for i in arr:
    sum += i

print(sum)

```

---

[View on HackerRank](https://www.hackerrank.com/challenges/diagonal-difference/problem)