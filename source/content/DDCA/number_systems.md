---
title: Number Systems
---
This comes directly from Harris and Harris' Book Digital Design and Computer Architecture.

# Basics
## Decimal System
This is our normal number system we use on a day to day basis, using base 10. Hence, every column has 10 times the weight of the column on the right. There really isn't much to add beyond that. Example: The number nineteen is represented as $19$, or $19_{10}$, where 10 stands for the basis.

## Binary System
This is the number system we use when dealing with technical devices and electricity.

| value | meaning           |
| ----- | ----------------- |
| 0     | off / low voltage |
| 1     | on / high voltage |
example: $1010_{2} = 1\cdot8 + 0\cdot 4 + 1 \cdot 2 + 0 \cdot 1 = 10_{10}$

### vocabulary
* most significant bit: leftmost bit
* least significant bit: rightmost bit

A neat trick to approximate values of power of two: 
![[Pasted image 20260221225524.png]]
### Binary Addition

## Hexadecimal System



## Conversion between different systems

### Neat tricks


## Signed vs Unsigned Binary Numbers



## Two's Complement
Motivation: Single representation for 0 (?) and binary addition works.

How to convert from a number to its negative? Consider the following signed 4-bit integer: $0101_{10} = 5_{10}$.
To take the two's compliment, we invert the digits (i.e. 0 becomes 1 and 1 becomes 0), then add 1.

Here: $0101_{2} \to 1010_{2} \space (inversion) \to 1011_{2} \space (add \space 1)$ = $-5_{10}$
The other direction is analogous: $1011_{2} \to 0100_{10} \space (inversion) \to 0101_2 (add \space 1) = 5_{10}$.

More generally: To take two's compliment, invert the digits and add 1.

### Addition (best explained with an example)
![[Pasted image 20260221234800.png]]
![[Pasted image 20260221235333.png]]

Left off at page 22, Chapter 1.6