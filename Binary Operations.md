---
tags:
  - softwaredd
  - flashcards
---

# Addition

What does binary addition look like and what are the rules?
1. Go from right to left
2. Write carry bits small above the numbers to be added.
3. Other rules:
![](https://i.imgur.com/vEJ6vF8.png)


# Subtraction

## 1's Compliment

How do you convert to **1's compliment**?
?
The original number with all its bits reversed.
eg. 00100101 --> 11011010


## 2's Compliment 

How do you convert to **2's Compliment**?
?
First do **1's Compliment** then add 1.


What is 2's compliment used for?
?
Binary Subtraction. Adding a binary number with a 2's compliment binary number results in a subtraction operation.


What are the 2 things that are important to remember about 2's compliment subtraction?
?
- Make sure both numbers have the correct number of bits. (you need to add 0's which are then converted to 1's though 1's Compliment)
- Drop any overflowing bits after the addition of the numbers. eg. if you end up with 9 bits after an 8 bit addition because of carry bits, drop the largest bit.


# Multiplication

What does binary multiplication look like and what are the rules?
?
- Very similar to normal multiplication
- If there is a 1, the line is copied, if a 0, then all bits are 0
- Each part is shifted by one column for each 2's place
- The result is added with binary addition
![](https://i.imgur.com/RnINuFm.png)


What does binary division look like and what are the rules?
?
- Very similar to long division
1. Find the first column where the divisor (111) is less than the above part of the dividend (1100101) and add a 1 to the correct place value of the result (quotient)
2. Subtract the divisor from the dividend
3. Bring down new bits if necessary before repeating the process
![](https://i.imgur.com/oOllHfR.jpg)

