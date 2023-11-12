# Homework No. 03

**Due:** 23:59, 22 October, 2023

**Max points:** 100

## Rules

- **No late homeworks.** A penalty of 10 points is applied for each day.
- **No plagiarism.** Collaboration is encouraged, but copying someone else's work without proper attribution is not admitted and invalidates the submission. A penalty is applied to all parties included.

## Submission procedure

- Each problem solution should be saved in a separate file. The following naming convention should be used: `problem{number}.{extension}`. For example, `problem1.py` or `problem1.pdf`.
- At the start of each file, homework number, student full name and problem number should be mentioned. For example:

```python
"""
Homework 3
Name: John Doe
Problem 1
"""
```

- Solution files should be uploaded to [YSU Moodle](https://e-learning.ysu.am/). Alternatively, you can commit your solutions to a Git repository and provide the repository URL on Moodle.

<div style="page-break-after: always;"></div>

## Problem 1 [20 points]
Pythagorean Triples Checker:
Accept three integer values and determine whether they form a Pythagorean triplet (a^2 + b^2 = c^2).

``` python
def is_pythagorean(a, b, c):
    pass

print(is_pythagorean(3, 4, 5)) # True
print(is_pythagorean(3, 4, 6)) # False
```

## Problem 2 [20 points]
List Chunking:
Write a function called chunk that divides a list into chunks of a specified size. For instance, given the list `[1, 2, 3, 4, 5, 6, 7, 8, 9]` and chunk size 4, the result should be `[[1, 2, 3, 4], [5, 6, 7, 8], [9]]`.

``` python
def chunk(l, size):
    pass

print(chunk([1, 2, 3, 4, 5, 6, 7, 8, 9], 4)) # [[1, 2, 3, 4], [5, 6, 7, 8], [9]]
```

## Problem 3 [20 points]
List Deduplication:
Implement a function that returns a new list with removed duplicates, but maintains the original order of the list.

``` python
def deduplicate(l):
    pass

print(deduplicate([1, 2, 3, 1, 2, 3, 4, 5])) # [1, 2, 3, 4, 5]
```

<div style="page-break-after: always;"></div>

## Problem 4 [20 points]
Missing Number Finder:
In a list containing numbers from 1 to 100, one number is missing. Write a function that finds the missing number.
    
``` python
def find_missing(l):
    pass

a = list(range(1, 101))
a.remove(42)
print(find_missing(a)) # 42
```

## Problem 5 [20 points]
List Rotation:
Implement a function that rotates a list to the left by k elements. For example, given the list `[1, 2, 3, 4, 5, 6]` and k = 2, the result should be `[3, 4, 5, 6, 1, 2]`.

``` python
def rotate(l, k):
    pass

print(rotate([1, 2, 3, 4, 5, 6], 2)) # [3, 4, 5, 6, 1, 2]
```

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config">
    MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });
</script>