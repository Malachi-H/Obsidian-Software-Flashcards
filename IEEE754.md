---
tags:
  - softwaredd
  - flashcards
---

How many bits in the IEEE754 format?
?
32

How many bits in the mantissa of the IEEE754 format?
?
23

How many bits in the exponent of the IEE754 format?
?

What are the steps to convert a binary number into the IEEE754 format?
?
1. Determine the sign of the number. If negative, the first bit (sign bit) is 1, otherwise it is 0.
2. Convert into the base 2 scientific notation format.
	- eg. 17.5$_{10}$   -->  10001.1$_{2}$  -->  1.00011x2${^4}$ 
3. Add 127 to the exponent (in this case 4) and convert it to binary.
	- 10000000${_{2}}$ --> 128${_{10}}$
	- 01111111${_{2}}$ --> 127${_{10}}$
	- Therefore, if the exponent is positive, you can simply subtract 1 from the exponent and add it to 10000000${_{2}}$ 
	- 4${_{10}}$ --> 100${_{2}}$ 
	- Therefore 4${_{10}}$+127${_{10}}$ = 10000100${_{2}}$ 
4. Drop the 1 at the beginning of the mantissa (number in front of the scientific notation part) and add 0s to make it 23 bits.
5. Finally, combine the components. S XXXXXXXX MMMMMMMMMMMMMMMMMMMMMMM where S = sign bit, X = exponent + bias of 127, M = mantissa without the 1 the beginning.