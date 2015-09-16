Crypthographic Hash function
==============================
Cryptographic hash function is the mathematical function with the following three propertis
1. Its input can be any size
2. It produce a fixed size output
3. It is efficently computable, this means that for a given input string, you can figure out the output of the hash fncion is resanoble amount of time, more techniallyy computing the hash of an n-bit string should have a running time taht is O(n)

For a hash function to be cryptographically secure, it has three addition properties
1. Collision Resistance
2. hiding
3. Puzzle friendliness

1. Collision resistance property
---------------------------------
A collision occurs when the two distinct inputs produes the same output.
Collision-resistance: A hash function H is said to be collision resistant if it is infeasible to find two
values, x and y, such that x ≠ y, yet H(x)=H(y).

In fact collision do occurs, because  The
input space to the hash function contains all strings of all lengths, yet the output space contains only
strings of a specific fixed length. Because the input space is larger than the output space (indeed, the
input space is infinite, while the output space is finite), there must be input strings that map to the
same output string. In fact there will generally be a very large number of possible inputs that map to
any particular output

One intersting, thing, Collision Occours, but it is impossible to find the collision
