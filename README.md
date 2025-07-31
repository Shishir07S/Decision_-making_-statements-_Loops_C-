# Decision_-making_-statements-_Loops_C-
# C++ Programs Collection

This repository contains several C++ programs that demonstrate basic programming concepts such as loops, patterns, and number sequences. These programs are designed to showcase different output patterns using simple C++ control structures.

---

## Table of Contents

1. [Number Sequence Printer](#number-sequence-printer)
2. [Diamond Star Pattern](#diamond-star-pattern)
3. [Pyramid Star Pattern](#pyramid-star-pattern)
4. [Inverted Pyramid Star Pattern](#inverted-pyramid-star-pattern)
5. [Alphabet Triangle](#alphabet-triangle)
6. [Hourglass Star Pattern](#hourglass-star-pattern)
7. [Simple Counter](#simple-counter)

---

## 1. Number Sequence Printer

### Aim:
The aim of this program is to print a sequence of numbers incrementally across rows based on user input. The number of rows is provided by the user.

### Theory:
This program utilizes **nested loops** to generate a pattern. The outer loop runs through the rows, and the inner loop prints the numbers in an increasing order.

### Algorithm:
1. Prompt the user for the number of rows.
2. Initialize a number counter (`num`).
3. Use an outer loop to iterate through each row.
4. For each row, print numbers incrementally using an inner loop.
5. Increment the number counter after each print.

### Conclusion:
This program demonstrates how nested loops can be used to format numbers into a structured pattern. It also highlights how to increment and manage variables within loops to control the output.

---

## 2. Diamond Star Pattern

### Aim:
This program is designed to print a diamond-shaped star pattern using stars (`*`). The size of the diamond is determined by a constant value (`n`).

### Theory:
The diamond pattern is made up of two parts: the upper and lower halves. Both halves are printed using nested loops. The upper half has fewer spaces and more stars, while the lower half reverses this pattern.

### Algorithm:
1. Set the total size of the diamond (`n`).
2. Use a loop to print the upper half of the diamond.
3. Print spaces before stars in each row.
4. Use another loop to print the lower half of the diamond.

### Conclusion:
The diamond star pattern demonstrates how to use loops and space management to format output. It also emphasizes the importance of symmetry in patterns.

---

## 3. Pyramid Star Pattern

### Aim:
This program prints a pyramid pattern made of stars (`*`), with the number of stars increasing with each row.

### Theory:
The pyramid pattern is constructed by using nested loops to print spaces and stars. As you go down the pyramid, the number of stars increases, while the spaces decrease to center-align the stars.

### Algorithm:
1. Use an outer loop to iterate through each row.
2. Print spaces before the stars on each row.
3. Print the appropriate number of stars for each row using an inner loop.

### Conclusion:
This program helps understand how to align text or characters in the center and create structured patterns using loops. It also reinforces the concept of increasing and decreasing values within loops.

---

## 4. Inverted Pyramid Star Pattern

### Aim:
The objective of this program is to print an inverted pyramid of stars. The number of stars decreases as the rows increase.

### Theory:
The inverted pyramid is similar to the regular pyramid pattern, but the number of stars decreases as the row number increases. The spaces before each row increase to maintain the inverted pyramid shape.

### Algorithm:
1. Start with a large number of stars in the first row.
2. Use a loop to print decreasing numbers of stars and increasing numbers of spaces.
3. Continue until all rows are printed.

### Conclusion:
This program highlights how to reverse the pattern of a typical pyramid. It demonstrates the application of loops for generating both increasing and decreasing sequences in a controlled manner.

---

## 5. Alphabet Triangle

### Aim:
This program prints a triangle pattern of alphabet letters starting from 'A' and incrementing for each subsequent letter.

### Theory:
The program uses a nested loop where each row starts printing characters in increasing order. The alphabet letters continue to increment from 'A' in a sequential manner across the rows.

### Algorithm:
1. Initialize a variable `ch` as 'A'.
2. Use an outer loop to print each row.
3. In each row, use an inner loop to print the letters sequentially.
4. After each letter, increment the variable `ch`.

### Conclusion:
This program demonstrates how characters can be manipulated and printed in a sequential pattern. It reinforces the use of ASCII values for letter incrementing and the concept of nested loops.

---

## 6. Hourglass Star Pattern

### Aim:
The goal of this program is to print an hourglass-shaped pattern of stars. The pattern has a wide upper part and narrows down towards the bottom.

### Theory:
An hourglass pattern is made of two parts: the upper part (wide) and the lower part (narrow). The program uses nested loops to create spaces and stars in both parts, adjusting the number of stars and spaces as it progresses.

### Algorithm:
1. Print the upper part of the hourglass using loops for spaces and stars.
2. Print the lower part of the hourglass using similar logic.
3. Adjust the number of stars and spaces in each part as the loop progresses.

### Conclusion:
This program illustrates how to manipulate spaces and stars to create complex shapes. It requires understanding how to combine loops for formatting and control over the printed pattern.

---

## 7. Simple Counter

### Aim:
This program uses a simple `while` loop to print numbers from 1 to 20.

### Theory:
A `while` loop is used here to repeatedly execute a block of code. In this case, the loop is used to print numbers one by one from 1 to 20, with the loop counter being incremented on each iteration.

### Algorithm:
1. Initialize a counter variable `i` as 0.
2. Use a `while` loop to check if `i` is less than 20.
3. Print the value of `i + 1`.
4. Increment `i` by 1.
5. Continue until `i` reaches 20.

### Conclusion:
This program demonstrates the use of a `while` loop for simple iteration. It is a basic example of a loop counter and how to control the flow of a program based on a condition.

---
