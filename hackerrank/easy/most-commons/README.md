# Python If-Else

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

A newly opened multinational brand has decided to base their company logo on the three most common characters in the company name. They are now trying out various combinations of company names and logos based on this condition. Given a string $s$, which is the company name in lowercase letters, your task is to find the top three most common characters in the string.

- Print the three most common characters along with their occurrence count.
- Sort in descending order of occurrence count.  
- If the occurrence count is the same, sort the characters in alphabetical order.   

For example, according to the conditions described above, 

$\color{green}\texttt{G}\color{red}\texttt{OO}\color{green}\texttt{G}\color{black}\texttt{LE}$ would have it's logo with the letters $\color{green}\texttt{G},\color{red}\texttt{O},\color{black}\texttt{E}$. 




**Input Format**

A single line of input containing the string $S$.  



**Constraints**

+ $ 3 < len(S) \le 10^4 $   
+ $S$ has at least $3$ distinct characters   

**Output Format**

Print the three most common characters along with their occurrence count each on a separate line.  
Sort output in descending order of occurrence count.  
If the occurrence count is the same, sort the characters in alphabetical order.

## Solution

**Language:** Python  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-07-16T17:27:33.774Z  

```py
n=int(input ())
if n%2==0:
    if n in range(2,6):
        print("Not Weird")
    elif n in range(6,21):
        print("Weird")
    elif n>20:
        print("Not Weird")
else:
    print("Weird")

```

---

[View on HackerRank](https://www.hackerrank.com/challenges/most-commons/problem)