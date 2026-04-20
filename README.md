# leetcode-solutions
My solutions to Leetcode problems with explanations (C++)

# Add Two Numbers

## Problem
Given two linked lists representing numbers in reverse order, return their sum as a linked list.

## Aproach
- Traverse both lists simultaneously
- Add digits along with carry
- Store result in a new linked list
- Continue until both lists and carry are exhausted

## Key Idea 
Simulate digit-by-digit addition with carry (like manual addition).

## Time Complexity
O(n)

## Space Complexity
O(n)

## Key Concepts
- Linked List
- Carry handling
- Simulation of addition

## Example
Input:
2 → 4 → 3   5 → 6 → 4

Output:
7 → 0 → 8

## Notes
Used dummy node to simplify list construction and avoid edge cases.

   


