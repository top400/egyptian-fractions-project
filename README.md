# Egyptian Fractions — Mathematical Theory and Python Implementation

## Introduction

This project explores Egyptian fractions and their mathematical properties.
Egyptian fractions were used in ancient Egypt to represent rational numbers
as sums of unit fractions.

A unit fraction is a fraction with numerator equal to 1, for example:

1/2, 1/3, 1/5, 1/10

In this project I study the theory behind Egyptian fractions and implement
an algorithm in Python that converts any fraction into a sum of unit fractions.

The goal of the project is to demonstrate how mathematical ideas from ancient
times can be implemented using modern programming tools.

---

## Project goals

- Explain what Egyptian fractions are
- Study the mathematical theory
- Implement the greedy algorithm
- Test the algorithm with different fractions
- Show how mathematics and programming work together

---

## Mathematical background

Egyptian fractions represent a rational number as a sum of distinct unit fractions.

Example:

2/3 = 1/2 + 1/6  
3/4 = 1/2 + 1/4  
5/6 = 1/2 + 1/3  

One important mathematical result states that every positive rational number
can be written as a sum of unit fractions.

One of the most common methods for finding such representation is the greedy algorithm.

---

## Algorithm

The greedy algorithm works as follows:

1. Given a fraction a/b
2. Find the smallest unit fraction 1/n such that

   1/n ≤ a/b

3. Subtract this unit fraction from the fraction
4. Repeat until the result becomes zero

This algorithm always produces a valid Egyptian fraction representation.

---

## Technologies used

- Python
- Jupyter Notebook
- fractions module
- math module
- GitHub

---

## Files in this repository

- egyptian_fractions.ipynb — main notebook with code and explanations
- README.md — project description

---

## Results

The implemented algorithm successfully converts fractions into Egyptian fractions.

Examples tested in the project:

2/3  
3/4  
5/6  
7/8    
9/10  
78/96  

The results confirm that the greedy algorithm works correctly.

---

## Conclusion

This project demonstrates how Egyptian fractions can be generated using
a simple algorithm.

The project combines mathematical theory, algorithmic thinking,
and Python programming.

It also shows how ancient mathematical ideas can still be useful today,
especially in computer science and number theory.