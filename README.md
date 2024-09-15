# BitMaskingAndManipulation

Welcome to **BitMaskingAndManipulation**! This repository provides a wide array of tools, algorithms, and examples for mastering bit manipulation and bitmasking techniques. Perfect for optimizing code and solving complex problems with efficiency.
| Operator | Symbol | Description                                      | Example                 |
|----------|--------|--------------------------------------------------|-------------------------|
| AND      | `&`    | Performs a bitwise AND operation.                | `0b1100 & 0b1010` -> `0b1000` |
| OR       | `|`    | Performs a bitwise OR operation.                 | `0b1100 | 0b1010` -> `0b1110` |
| XOR      | `^`    | Performs a bitwise XOR (exclusive OR) operation. | `0b1100 ^ 0b1010` -> `0b0110` |
| NOT      | `~`    | Performs a bitwise NOT (inversion) operation.    | `~0b1100` -> `0b0011` (assuming 4-bit representation) |
| LEFT SHIFT | `<<` | Shifts bits to the left, fills with zeros.      | `0b0011 << 2` -> `0b1100` |
| RIGHT SHIFT | `>>` | Shifts bits to the right, fills with zeros or sign bits depending on the system. | `0b1100 >> 2` -> `0b0011` |

| Operation      | Description                                      | Example Usage                      | Result             |
|----------------|--------------------------------------------------|-----------------------------------|--------------------|
| Bitwise AND    | Compares each bit of two numbers, results in 1 if both bits are 1. | `0b1100 & 0b1010` | `0b1000` |
| Bitwise OR     | Compares each bit of two numbers, results in 1 if either bit is 1. | `0b1100 | 0b1010` | `0b1110` |
| Bitwise XOR    | Compares each bit of two numbers, results in 1 if bits are different. | `0b1100 ^ 0b1010` | `0b0110` |
| Bitwise NOT    | Inverts all the bits of the number.             | `~0b1100` (in 4-bit representation) | `0b0011` |
| Left Shift     | Shifts bits to the left, zero-filled.           | `0b0011 << 2` | `0b1100` |
| Right Shift    | Shifts bits to the right, zero-filled (or sign-extended). | `0b1100 >> 2` | `0b0011` |


| Algorithm             | Description                             | Example Use Case                        |
|-----------------------|-----------------------------------------|-----------------------------------------|
| Bit Masking           | Apply masks to isolate bits.            | Extract specific flags from an integer. |
| Bit Shifting          | Shift bits left or right.               | Multiply/divide by powers of 2.         |
| Bit Counting          | Count the number of set bits.           | Count active flags in a status word.    |
| Bit Reversal          | Reverse the order of bits.              | Useful in certain hashing algorithms.   |


