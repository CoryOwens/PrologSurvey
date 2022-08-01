If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.

Find the sum of all the multiples of 3 or 5 below 1000.

----

Generalized:

Create a function `f(x)`, which returns the sum all integers `i<x`, where `i` is divisible by `3` or `5`.

----

Human Hint: an integer is divisible by `5` if its last digit (the "ones digit") is `5` or `0`.

Human Hint: an integer is divisible by `3` if the sum of its digits is divisible by `3`. (This can lead to a recursive algorithm where you repeat until you hit a number you _know_ is a multiple of `3` from past experience, but can be repeated until you have a 1-digit number, which you can easily check mentally).
