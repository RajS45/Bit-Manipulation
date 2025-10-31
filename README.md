# Bit-Manipulation
-> Problem on Bit Manipulation and important concepts

Bit Manipulation
Bit manipulation is the technique of working directly with the binary representation of numbers.
Every number in a computer is stored as a sequence of bits—0s and 1s. 
Bit manipulation allows you to perform operations on these bits to achieve tasks more efficiently than using standard arithmetic.

Use Bit Manipulation
- Speed: Bitwise operations are extremely fast because they are directly supported by the processor.
- Memory Efficiency: You can store multiple flags or states in a single integer using bits.
- Control: It gives you fine-grained control over data, especially useful in low-level programming, embedded systems, and performance-critical applications.

Common Bitwise Operations
- AND (&): Compares each bit of two numbers and returns 1 only if both bits are 1.
- OR (|): Returns 1 if at least one of the bits is 1.
- XOR (^): Returns 1 if the bits are different.
- NOT (~): Flips all the bits (0 becomes 1, and 1 becomes 0).
- Left Shift (<<): Shifts bits to the left, effectively multiplying by powers of 2.
- Right Shift (>>): Shifts bits to the right, effectively dividing by powers of 2.

Real-Life Examples
- Checking if a number is even or odd: Use num & 1. If the result is 1, it's odd; if 0, it's even.
- Swapping two numbers without a temporary variable: Use XOR.
- Counting the number of set bits (1s): Loop through the bits and count how many are set.
- Setting, clearing, or toggling specific bits: Use combinations of AND, OR, and XOR with bit masks.

Example in Java
int a = 5;      // binary: 0101
int b = 3;      // binary: 0011
int result = a ^ b;  // result: 0110 (binary), which is 6


This XOR operation highlights the bits that differ between a and b.

Let me know if you'd like to explore specific tricks like checking powers of two, bit masking, or optimizing algorithms with bits!



