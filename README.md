# CS-251-Computer-Architecture-and-Assembly-Language

These are rudimentary projects provided by Dr. Scott Summers, that I coded and submitted in my CS-251 class.

To prevent anyone, and myself for that matter, from violating University of Wisconsin - Oshkosh's Academic Honesty Policy,
I do not condone or grant the reuse and resubmission of these projects under another student's name. This repository is here to serve as a portfolio. That being said, these projects are licensed under **agpl-3.0**. Follow github's licensing policy and copyright laws.

Feel free to download and test my submitted code. These were coded in C using GNU nano and in MIPS using MARS.

Alex

## Lab 1 ##

A C program that prompts the user to enter a valid unsigned short int and then the program prints out the low order
16 bits in the binary representation of the input as well as the number of 0 bits in the low order bits thereof.

## Lab 2 ##

A C program that takes as input two unsigned short int values from the user, adds the two
input values together and then outputs the result in binary.

## Lab 3 ##

A C program that takes as input a sequence of at least two bits and at most 100 bits, followed by either a + or -, followed by another sequence of at least two bits and most 100 bits, terminated by the user hitting the enter key, and no spaces anywhere in the input. The sequence of bits before the + or - is the first input operand, and the sequence of bits after the + or - is the second input operand. The program will interpret the the input as an arithmetic operation involving two operands, both in two’s complement. Then, the program will compute and output the result of the operation.

## Lab 4 ##

A C program that converts a binary floating point value entered by the user to decimal, where the decimal part is represented as a sum of powers of two, e.g., your program must convert 01100.1011 to 12 + 1/2 + 1/8 + 1/16. The input format, which the user will always obey, is comprised of a string of at least 
one and at most 32 bits, followed by a period, followed by a string of at least one and at most 16 bits.

## Lab 5 ##

A C program that lets the user type in an arbitrary positive number of bits (consecutively, with no whitespace in between) and outputs the result of
flipping the bits that were just input and adding one to the result. 

## Lab 6 ##

A short C program that takes no input, and allows the user to discern from the output the endianness of their machine.

## Lab 7 ##

A relatively short MIPS program that reads in two integers from the user (unprompted), and then outputs the sum of all the positive integers between
(and including) the two inputs. 

## Lab 8 ##

A MIPS program that takes as input a four-digit integer greater than or equal to 1853, and outputs whether it represents a valid leap year.

## Lab 9 ##

A MIPS program that allows the user to perform access and update operations on a two dimensional array of ints. The basic idea behind the C program will be to declare a two dimensional int array with 79 rows and 112 columns, prompt the user to enter row and column indices, and, if these indices are valid, the current value in the array at that location is printed out, and then the program prompts the user for a new value to be stored at that same location, overwriting the old value. If either (row or column) index is invalid, then the program terminates. 
