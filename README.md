# Geometric Progression Calculator

This project calculates the n-th term of a geometric progression.

# Description

A geometric progression is a sequence of numbers:

b₁, b₂, ..., bₙ

where each next term is obtained by multiplying the previous one by a constant value `q` (the common ratio).

The formula for the n-th term is:

bₙ = b₁ · q^(n − 1)

# Input

The program receives three integers, each on a separate line:

- `b₁` — the first term of the progression  
- `q` — the common ratio  
- `n` — the term index to compute  

# Output

The program outputs the n-th term of the geometric progression.


# Implementation (Python)

```python
b = int(input())
q = int(input())
n = int(input())

s = n - 1
print(b * q ** s)
