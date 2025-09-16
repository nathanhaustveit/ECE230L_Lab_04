# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

Summarize your learnings from the lab here.

In this lab, we learned how to use a k-map to minimize and optimize boolean equations. 
We compared a naieve equation to midterm and maxterm optomized equations and then simulated 
them to verify our design for correctness and that the LEDs match. 

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?

Because only one input one both axis change from column to column and row to row and this extends to edges.

### Why are the names Sum of Products and Products of Sums?

For SOP, the boolean algebraic expression is represented as a bunch of multiplication equations being added together. This is essentially a bunch hof AND statements being OR together.
For POS, the boolean algebraic expression is represented as a bunch of sum equations being muliplied together. This represents a bunch of OR statements being AND together.

### Open the test.v file – how are we able to check that the signals match using XOR?

It compares two LEDs, and if their values don't match, then the output is 1, it passes through the if statement, and the test finishes.
