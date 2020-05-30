# Canadian Computing Competition (CCC) Problems

https://cemc.math.uwaterloo.ca/contests/past_contests.html#ccc

## 1. Problem J1: Dog Treats

### Problem Description

Barley the dog loves treats. At the end of the day he is either happy or sad depending on the
number and size of treats he receives throughout the day. The treats come in three sizes: small,
medium, and large. His happiness score can be measured using the following formula:
1 × S + 2 × M + 3 × L
where S is the number of small treats, M is the number of medium treats and L is the number of
large treats.
If Barley’s happiness score is 10 or greater then he is happy. Otherwise, he is sad. Determine
whether Barley is happy or sad at the end of the day.

### Input Specification

There are three lines of input. Each line contains a non-negative integer less than 10. The first line
contains the number of small treats, S, the second line contains the number of medium treats, M,
and the third line contains the number of large treats, L, that Barley receives in a day.

### Output Specification

If Barley’s happiness score is 10 or greater, output happy. Otherwise, output sad.

## 2. Problem J2: Epidemiology

### Problem Description

People who study epidemiology use models to analyze the spread of disease. In this problem, we
use a simple model.
When a person has a disease, they infect exactly R other people but only on the very next day. No
person is infected more than once. We want to determine when a total of more than P people have
had the disease.
(This problem was designed before the current Coronavirus outbreak, and we acknowledge the
distress currently being experienced by many people worldwide because of this and other diseases.
We hope that including this problem at this time highlights the important roles that computer
science and mathematics play in solving real-world problems.)

### Input Specification

There are three lines of input. Each line contains one positive integer. The first line contains the
value of P. The second line contains N, the number of people who have the disease on Day 0. The
third line contains the value of R. Assume that P ≤ 107
and N ≤ P and R ≤ 10.

### Output Specification

Output the number of the first day on which the total number of people who have had the disease
is greater than P.

## 3. Problem S1: Don’t pass me the ball!

### Problem Description

A CCC soccer game operates under slightly different soccer rules. A goal is only counted if the
4 players, in order, who touched the ball prior to the goal have jersey numbers that are in strictly
increasing numeric order with the highest number being the goal scorer.
Players have jerseys numbered from 1 to 99 (and each jersey number is worn by exactly one
player).
Given a jersey number of the goal scorer, indicate how many possible combinations of players can
produce a valid goal.

### Input Specification

The input will be the positive integer J (1 ≤ J ≤ 99), which is the jersey number of the goal
scorer.

### Output Specification

The output will be one line containing the number of possible scoring combinations that could
have J as the goal scoring jersey number.
