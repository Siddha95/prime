# Implementation Details
The easiest way to check if a number is prime, is to try dividing it by every number from 2 up to, but not including, the number itself. If any number divides into it with no remainder, that number is not prime.

The main function in the distribution code contains a for loop that iterates through the range specified by the user, with both ends inclusive. For example, if the user types in 1 for min and 100 for max, the for loop will test each number, 1 to 100. Each of these numbers is passed to a function, prime, that you will implement to return either true or false depending on whether the number is prime.

## Thought Question
Can you make the prime-finding algorithm more efficient than checking if a number is divisible by every number between 2 and 1 less than itself? Can you think of another way to generate prime numbers?

## How to Test Your Code
Your program should behave per the examples below.

prime/ $ ./prime
Minimum: 1
Maximum: 100
2
3
5
7
11
13
17
19
23
29
31
37
41
43
47
53
59
61
67
71
73
79
83
89

## Instructions 
To make this code work just compile it with '$ make prime' and run '$ ./prime' to see the result.
97
