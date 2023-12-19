# CS 181 Lab Assignment 1

**Due:** Wednesday, January 24, 2024

**Sample Solution Length:** 52 Lines (including comments)

## Individual Work

All assignments in this course are to be completed individually. Students are advised to read the guidelines for avoiding plagiarism located on the course website. Students are also advised that electronic tools may be used to detect plagiarism.

## Late Penalty:

Late assignments will not be accepted.

## Logistics

**Submission Instructions:** Upload your solution, entitled `YourFirstName-YourLastName-Lab01.py` to the Canvas Lab 1 Dropbox.

**Deadline Reminder:** Once this deadline passes, Canvas will no longer accept your Python submission and you will no longer be able to earn credit. Thus, if you are not able to fully complete the assignment, submit whatever you have before the deadline so that partial credit can be earned.

## Learning Outcomes

* Gain experience using the Python calendar module.

## Assignment

Use the calendar module to write a program that asks the user when they were born and then uses that information to produce this output. In the transcript, the user was born on October 15, 2004, but make sure your program works for any valid date.

### Example Output:

```
Enter your birth year: 2004
Enter your birth month [1-12]: 10
Enter your birth day [1-31]: 15

Your birthday day (Monday=0, Tuesday=1, etc.) is 4
Your birth year is a leap year = True

Your birth month calendar where Monday is the leftmost day:

    October 2004
Mo Tu We Th Fr Sa Su
             1  2  3
 4  5  6  7  8  9 10
11 12 13 14 15 16 17
18 19 20 21 22 23 24
25 26 27 28 29 30 31

Your birth month calendar where Sunday is the leftmost day:

    October 2004
Su Mo Tu We Th Fr Sa
                1  2
 3  4  5  6  7  8  9
10 11 12 13 14 15 16
17 18 19 20 21 22 23
24 25 26 27 28 29 30
31

The leap years from your birth year to 2024 are:

1. 2004
2. 2008
3. 2012
4. 2016
5. 2020 
6. 2024
```

## Grading - 10 points

- 1 point. For any valid input, the person's birthday day number (e.g. 4 in the sample output) is identified correctly.
- 1 point. For any valid input, the person's birth year is correctly identified as a leap year (or not) with the word True (or False).
- 1 point. The birth month calendar where Monday is the leftmost day is printed correctly.
- 1 point. The birth month calendar where Sunday is the leftmost day is printed correctly.
- 2 points. The leap years from the person's birth year through 2024 are all correctly printed.
- 2 points. The program runs without any errors.
- 2 points. The output format is matched exactly. For each type of difference, 1 point will be lost.

## Grading Turnaround

All labs and programming assignments should be graded with scores recorded in Canvas no later than the Monday following their due date.