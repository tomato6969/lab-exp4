Experiment No. 4

Aim: : To study and implement bitwise operators in C++.

Tools Required:

Visual Studio Code (VS Code)

Theory:

Bitwise operators perform operations on the binary representation of data. These operators are commonly used in low-level programming, embedded systems, and for optimizing certain algorithms.

1.Bitwise Operators Table

Operator Description Example Result

& Bitwise AND 5 & 3 = 1
	 Bitwise OR
^ Bitwise XOR 5 ^ 3 = 6
~ Bitwise NOT ~5 = -6
<< Left Shift (multiplies by 2^n) 5 << 1 = 10
Right Shift (divides by 2^n) 5 >> 1 = 2

Example Code Concept:

syntax:

int a = 5; // Binary: 0101

int b = 3; // Binary: 0011

int result1 = a & b; // AND: 0001 → 1

int result2 = a | b; // OR: 0111 → 7

int result3 = a ^ b; // XOR: 0110 → 6

int result4 = ~a; // NOT: 1010 → -6 (2's complement)

int result5 = a << 1; // Left Shift: 1010 → 10

int result6 = a >> 1; // Right Shift: 0010 → 2

Conclusion:

By performing this experiment:

You learned how data is manipulated at the binary level using bitwise operators.

You successfully implemented bitwise AND, OR, XOR, NOT, left shift, and right shift.

You understood how these operators can be used for optimizing arithmetic and logical tasks in system-level programming
