Fibonacci Function
Overview: The Fibonacci function calculates the nth number in the Fibonacci sequence. The sequence is defined as:

fibonacci(0) = 0
fibonacci(1) = 1
fibonacci(n) = fibonacci(n-1) + fibonacci(n-2) for n > 1
Implementation Details:

Basic Recursive Approach:

Utilizes a simple recursive method to compute the Fibonacci number.
Suitable for small values of n.
Optimized Approach with Memoization:

Incorporates memoization to store and reuse previously computed values.
Reduces redundant calculations and improves performance, making it efficient for larger values of n.
Complexity:

Basic Recursive: Exponential time complexity 
𝑂
(
2
𝑛
)
O(2 
n
 ).
Memoized: Linear time complexity 
𝑂
(
𝑛
)
O(n), with additional space complexity for storing results.
Examples:

fibonacci(0) returns 0
fibonacci(1) returns 1
fibonacci(5) returns 5
fibonacci(10) returns 55
Usage:

The basic recursive implementation is best suited for educational purposes or small inputs.
The memoized implementation is recommended for applications requiring efficient computation of large Fibonacci numbers.
