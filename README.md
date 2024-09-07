# Booth_4

Overview
This project implements a 4-bit Booth multiplier in Verilog. Booth's algorithm is an efficient method for multiplying two signed binary numbers in two's complement representation. The Verilog code provided multiplies two 4-bit signed numbers and produces an 8-bit signed product.

Booth's Algorithm:
Booth's algorithm reduces the number of addition/subtraction operations required in binary multiplication by encoding the multiplier using bit-pair recoding. It checks consecutive pairs of bits and performs arithmetic shifts and additions based on the bit-pair value.

Features:
Handles signed 4-bit multiplication using two's complement.
Produces a signed 8-bit product.
Efficient and reduces the complexity of multiplication using Booth's encoding.
