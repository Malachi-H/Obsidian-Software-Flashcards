---
tags:
  - softwaredd
  - flashcards
---

## Files

### Relative files

What is the structure of a relative file?
?
Record Like sections of a fixed length. A key is used to determine the placement in file


What is the pseudocode of opening a relative file?
?
"Open *Filename* for relative access"
(Relative files can be read form and written to with the same opening and without needing to be closed and reopened)


What is the pseudocode for reading from a relative file?
?
"Read *Filename* into *Field1, Field2*, ... ,*FeildN* using *Key*"


### Sequential Files

What are the characteristics of a sequential file?
?
- Data is stored in a continuous steam.
- Data must be read sequentially - beginning to end 
- Sentinel values such as EOF can be used


What is the pseudocode for opening a sequential file?
?
"Open *Filename* for *Method*"
Where method can be:
- Input: read from file (input into program)
- Output: write to file (output from program)
	- Overwrites all data already in the file
- Append: Adds to the end of the file 
	- Leaves the contents of the file intact


What is the pseudocode used to read from a sequential file?
?
"Read *field1, field2, ..., fieldN*" from *filename*"


What is the pseudocode for writing to a sequential file?
?
"Write *filename* from *field1, field2, ..., fieldN*"
