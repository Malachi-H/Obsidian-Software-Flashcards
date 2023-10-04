---
tags:
  - softwaredd
  - flashcards
---
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

In a railroad diagram, what shape encloses non-terminal symbols?
?
Rectangle


What does a rectangle enclosing a section in a railroad diagram mean?
?
A non-terminal symbol


___

In a railroad diagram, what shape encloses terminal symbols?
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
