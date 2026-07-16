# Integers Come In All Sizes

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

You are given a positive integer $N$. Print a numerical triangle of height $N-1$ like the one below:  

    1
    22
    333
    4444
    55555
    ......
    
Can you do it using only **arithmetic operations, a single *for* loop and print statement?**  

Use no more than two lines. The first line (the *for* statement) is already written for you. You have to complete the print statement.  

**Note**: Using anything related to strings will give a score of $0$.  


**Input Format**  
A single line containing integer, $N$.  

**Constraints**  
$1 \le N \le 9$  

**Output Format**  
Print $N-1$ lines as explained above.  

**Sample Input**  

    5

**Sample Output**  

	1
    22
    333
    4444



**Input Format**

 

**Output Format**

## Solution

**Language:** Python  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-07-16T16:57:19.153Z  

```py
# Enter your code here. Read input from STDIN. Print output to STDOUT
a=int(input())
b=int(input())
c=int(input())
d=int(input())
result=(a**b)+(c**d)
print(result)

```

---

[View on HackerRank](https://www.hackerrank.com/challenges/python-quest-1/problem)