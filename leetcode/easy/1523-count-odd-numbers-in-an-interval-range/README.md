# Count Odd Numbers in an Interval Range

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

Given two non-negative integers `low` and `high`. Return the  *count of odd numbers between* `low` *and* `high` *(inclusive)*.

 

Original
Python3
 **Example 1:** 

```
Input: low = 3, high = 7
Output: 3
Explanation: The odd numbers between 3 and 7 are [3,5,7].
```

 **Example 2:** 

```
Input: low = 8, high = 10
Output: 1
Explanation: The odd numbers between 8 and 10 are [9].
```

 

 **Constraints:** 

- 0 <= low <= high <= 10^9

## Solution

**Language:** Python  
**Runtime:** 43 ms (beats 76.75%)  
**Memory:** 19 MB (beats 87.47%)  
**Submitted:** 2026-11-20T06:22:21.196Z  

```py
class Solution:
    def countOdds(self, low: int, high: int) -> int:
        return (high+1)//2-(low//2)
        
```

---

[View on LeetCode](https://leetcode.com/problems/count-odd-numbers-in-an-interval-range/)