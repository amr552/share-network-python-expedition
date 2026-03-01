# Assignment 01 (Python)

You are going to write a program that automatically prints the solution to the FizzBuzz game. These are the rules of the FizzBuzz game:

- Your program should print each number from 1 to 100 in turn and include number 100.
- But when the number is divisible by 3 then instead of printing the number it should print "Fizz".
- When the number is divisible by 5, then instead of printing the number it should print "Buzz".
- And if the number is divisible by both 3 and 5 e.g. 15 then instead of the number it should print "FizzBuzz"

e.g. it might start off like this:

1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz

...etc


# Assignment 02 — Grading Program

You have access to a database of student_scores in the format of a dictionary. The keys in student_scores are the names of the students and the values are their exam scores.

Write a program that converts their scores to grades.

By the end of your program, you should have a new dictionary called student_grades that should contain student names as keys and their assessed grades for values.

The final version of the student_grades dictionary will be checked.

DO NOT modify lines 1-7 to change the existing student_scores dictionary.
Scoring criteria

    Scores 91 - 100: Grade = "Outstanding"
    Scores 81 - 90: Grade = "Exceeds Expectations"
    Scores 71 - 80: Grade = "Acceptable"
    Scores 70 or lower: Grade = "Fail"

  
# Assignment 03 — Prime Number Checker

Prime numbers are numbers that can only be cleanly divided by themselves and 1.

You need to write a function called is_prime() that checks whether if the number passed into it is a prime number or not. It should return True or False.

e.g.

7 is a prime number because it is only divisible by 1 and itself.

But 4 is not a prime number because you can divide it by 1, 2 or 4.

NOTE: 2 is a prime number because it's only divisible by 1 and itself, but 1 is not a prime number because it is only divisible by 1.

Example Input 1 73

Example Output 1 True

Example Input 2 75

Example Output 2 False 

## What to submit
- File name: `assignment1.py`

## How to run
```bash
python assignment1.py
```
