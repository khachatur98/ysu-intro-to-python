# Homework No. 02

**Due:** 23:59, 24 September, 2023

**Max points:** 100

## Rules

- **No late homeworks.** A penalty of 10 points is applied for each day.
- **No plagiarism.** Collaboration is encouraged, but copying someone else's work without proper attribution is not admitted and invalidates the submission. A penalty is applied to all parties included.

## Submission procedure

- Each problem solution should be saved in a separate file. The following naming convention should be used: `problem{number}.{extension}`. For example, `problem1.py` or `problem1.pdf`.
- At the start of each file, homework number, student full name and problem number should be mentioned. For example:

```python
"""
Homework 2
Name: John Doe
Problem 1
"""
```

- Solution files should be uploaded to [YSU Moodle](https://e-learning.ysu.am/). Alternatively, you can commit your solutions to a Git repository and provide the repository URL on Moodle.

<!-- $$\pagebreak$$ -->

## Problem 1 [20 points]

Write a Python program that computes and displays the values of the following expressions:

1. $$\frac{1.2 \times 3.67^4 - 4.3^2 \times 14.89 \times 5.2}{1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9}$$

2. $$\frac{1^3 + 2^3 + 3^3 + 4^3 + 5^3}{(56 \times 47) \bmod 13 - 4 ^ {5 ^ 6} \bmod 7 }$$

## Problem 2 [20 points]

Write a program that allows the users to play the scissor, rock, paper game. The rules are as follows:

- A scissor can cut a paper
- A rock can knock a scissor
- A paper can wrap a rock

The program prompts both players to enter their choices displays a message indicating which player wins or if there is a draw.

The following shows an example program in action.

```sh
$ python problem2.py
Player 1: rock
Player 2: paper
Player 2 wins.
```

```sh
$ python problem2.py
Player 1: scissor
Player 2: scissor
It is a draw.
```

<div style="page-break-after: always;"></div>

## Problem 3 [20 points]

Body mass index (BMI) is a measure derived from the height and weight of a person. It can be calculated by dividing person's weight in kilograms by the square of their height in meters, i.e.:

$$BMI = \frac{weight}{height^2}$$

The health of a person can be measured using the following interpretation:

| Category    | BMI                 |
|-------------|---------------------|
| Underweight | $BMI < 18.5$        |
| Normal      | $18.5 \le BMI < 25$ |
| Overweight  | $25 \le BMI < 30$   |
| Obese       | $30 \le BMI$        |

Write a Python program that asks the user to enter their weight in kilograms and height in meters, and displays their BMI value and category.

The following shows an example program in action.

```sh
$ python problem3.py
Enter weight in kg: 75
Enter height in m: 1.8
BMI is 23.15.
BMI category is Normal.
```

<div style="page-break-after: always;"></div>

## Problem 4 [20 points]

Write a program that asks the user to enter an integer and outputs `True` if the provided number is a power of $2$. Otherwise, it displays `False`.

**Note:** Use `math` module.

The following shows an example program in action.

```sh
$ python problem4.py
Enter an integer: 8
True
```

```sh
$ python problem4.py
Enter an integer: 9
False
```
<!-- $$\pagebreak$$ -->

## Problem 5 [20 points]

Write a Python program that prompts the user to enter real number values for $a$, $b$ and $c$ and solves the following equation:

$$ax^2 + bx + c = 0$$

If the equation has one root or repeated roots, the program should display the single root. If the equation has two roots, both roots should be displayed. If the equation has no real roots, its complex roots should be displayed. Otherwise, the program should display that the equation has no roots.

The following shows an example program in action.

```sh
$ python problem6.py
Enter a: 1
Enter b: -1
Enter c: -6
The roots are -2 and 3.
```

```sh
$ python problem6.py
Enter a: 0
Enter b: 2.5
Enter c: -4.4
The root is 1.76.
```

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config">
    MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });
</script>