---
tags:
  - softwaredd
  - flashcards
---

# Circuits
# Logic Gates

How do you layout a truth table?
?
Letters for the values with all the possible values below them. eg.
The following columns have the boolean algebra notation for the gate or letters corresponding to a graph.
![[Circuits#^15c42b]]

## Not Gate

What does a not gate look like?
?
![](https://i.imgur.com/0hwF5lH.png)


What is the truth table of a not gate?
?
![](https://i.imgur.com/sRTF0pq.png)


What is the Boolean Algebra notation for a not gate?
?
![](https://i.imgur.com/U7Nv5uB.png)


## AND Gate

What does an AND Gate look like?
?
![](https://i.imgur.com/c44qadC.png)


What is the truth table for the AND Gate?
?
![](https://i.imgur.com/GSdcHO7.png)


What is the boolean algerbra notation for the AND gate between A and B?
?
![](https://i.imgur.com/2bLJnEX.png)



## NAND Gate

What does the NAND gate look like?
?
![](https://i.imgur.com/tHAD22i.png)


How is the NAND gate different from the AND gate?
?
The output is the not-ed version of an and.


What is the truth table for a nand gate?
?
![](https://i.imgur.com/oda0mr8.png)


What is the Boolean Algebra Notation for a NAND gate between A and B?
?
![](https://i.imgur.com/xSUb4ZA.png)



## OR Gate

What does the OR Gate look like?
?
![](https://i.imgur.com/LvSI4Ff.png)


What does the OR Gate truth table look like?
?
![](https://i.imgur.com/kR3Qi3k.png)


## NOR gate

What does NOR gate stand for?
?
Not Or


What does the NOR Gate look like?
![](https://i.imgur.com/lggQl3Y.png)

What is the Nor Gate's truth table?
?
![](https://i.imgur.com/7AV9aIk.png)


What is the boolean algebra notation for NOR?
?
![](https://i.imgur.com/eCyJMSh.png)



## XOR Gate

What does an XOR gate look like?
?
![](https://i.imgur.com/I21KWFt.png)


What is the truth table for an xor gate?
?
![](https://i.imgur.com/uym0HcJ.png)


How is an xor gate different from an or gate?
?
It returns 0 if both inputs are 1. 


What is the Boolean Algebra notation for a XOR gate between A and B?
?
![](https://i.imgur.com/BGPh4ty.png)


What does the XOR gate stand for?
?
Exclusive Or


## XNOR Gate

What does a XNOR Gate look like?
?
![](https://i.imgur.com/8DIVwdh.png)


How is the XNOR Gate different from the XOR Gate?
?
The result is not-ed


What is the truth table for the XNOR Gate?
?
![](https://i.imgur.com/M95twUx.png)


What is the Boolean Algebra notion for the XNOR Gate?
?
![](https://i.imgur.com/oTfAlEU.png)


What does XNOR stand for?
?
Exclusive Not Or



# Boolean Algebra Simplification

How do you write A or B in Boolean Algebra?
?
A + B


How do you wite A and B in Boolean Algebra?
?
AB 
or 
A.B


How do you write not A?
![](https://i.imgur.com/9gxh3HX.png)

How do you write A XOR B?
?
![](https://i.imgur.com/f5VQkLu.png)


How can you simplify:
(A+B)(A+C)
?
A+BC
Think of it as similar to the multiplication distribution except with addition.


How do you simplify:
![](https://i.imgur.com/2wFmOV1.png)
?
![](https://i.imgur.com/v1LjVlW.png)
The Or changes to an And and the Not signs get distributed to each variable.


How do you simplify:
![](https://i.imgur.com/qoAF1f0.png)
?
![](https://i.imgur.com/OkP5c0D.png)
The And changes to a Or and the Not signs get distributed to each variable.


How do you simplify:
A + AB
?
A


How do you simplify:
![](https://i.imgur.com/qFOcMuH.png)
?
A⊕B


How do you remove the XOR in A⊕B?
?
![](https://i.imgur.com/qFOcMuH.png)


# Half Adder

What does the half adder circuit look like?
?
![](https://i.imgur.com/n46NCQb.png)


What are the outputs of a half adder?
?
- Sum 
- Carry


What are the gates in a half adder?
?
XOR and AND


How many inputs and outputs does a half adder have?
?
2 and 2


Why would you use a half adder instead of a full adder?
?
If you don't have a carry bit input


# Full Adder

What does a full adder look like? (full gates)
?
![](https://i.imgur.com/zB79RsC.png)


What does a full adder look like? (Half Adders)
?
![](https://i.imgur.com/ylQiHvD.png)

What are the components of a full adder?
?
Two half adders and an Or gate


How many gates in a full adder?
?
5


How many inputs and outputs does a full adder have?
?
3 and 2


# Bistable Circuits 

What is another term for a latch circuit?
?
Flip-Flop

## NOR Latch

What does an RS latch using nor gates look like?
?
![](https://i.imgur.com/BXrE2tJ.png)


Is an RS Latch that uses NOR Gates active high or active low?
?
Active High


Is Q or NOT Q opposite R in an RS Latch using NOR Gates?
?
Q


Is Q or NOT Q opposite S in an RS Latch using NOR Gates?
?
NOT Q


## NAND Latch

What does an RS latch using nor gates look like?
?
![](https://i.imgur.com/281WoHJ.png)


Is an RS Latch that uses NAND Gates active high or active low?
?
Active Low


Is Q or NOT Q opposite R in an RS Latch using NAND Gates?
?
NOT Q


Is Q or NOT Q opposite S in an RS Latch using NAND Gates?
?
Q


# Syntax Definitions
## EBNF (Extended Bachus Naur Form)

What is EBNF?
?
A Metalanguage used to define the syntax of a programming language


What does "=" mean in EBNF?
?
"is defined as"


What does "|" mean in EBNF?
?
Binary Choice. 


What does "<...>" mean in EBNF?
?
A Non-Terminal sequence eg. a variable or separately defined syntax element.


What does "[...]" mean in EBNF?
?
0 or 1 times. eg. optional


What does "{...}" mean in EBNF?
?
Repetition (0 or more times)


What does "(...)" mean in EBNF?
?
Grouping section. Used to distinguish what parts of the expression are effected by another element, eg "*thing1* | (*thing2* | *thing3*)"


What is a terminal symbol in an EBNF Diagram?
?
A symbol which appears directly as it is depicted. ie. Not a variable


## Railroad Diagrams

What is a railroad diagram?
?
Graphical way to define a programming language's syntax

___

What shape encloses non-terminal symbols?
?
Rectangle

What does a rectangle enclosing a section in a railroad diagram mean?
?
A non-terminal symbol

___

What shape encloses terminal symbols?
?
Circle / Rounded Rectangle

What does a Circle / Rounded Rectangle enclosing a section in a railroad diagram mean?
?
A terminal symbol

___

What does terminal symbol mean?
?
A symbol that appears exactly as it is shown. (not a variable)

What is a non-terminal symbol?
?
A symbol that represents another section of syntax or variable.



# Table Format

|  A   |  B  | A+B |
|:---:|:---:|:----:|
|  0  |   0   |   0   |
|  0  |   1    |   1   |
|  1  |    0   |   1   |
|  1  |    1   |   1   |

^15c42b

