---
tags:
  - softwaredd
  - flashcards
---

### Internals of a CPU

##### Fetch Execute Cycle

What are the stages in the fetch execute cycle and what is done at each step?
?
1. Fetch
	- Instruction fetched from the memory location indicated by the program counter. 
2. Decode
	- Decodes the instruction to a form that can be executed by the **ALU** or **FPU**
3. Execute 
	-  The instruction is carried out
4. Store
	- The result of the instruction is stored in the accumulator or one of the program registers


##### Components

What is a **Data Bus**?
?
A system to allow the transport of data (within the CPU)


What does **ALU** mean and what does it do?
?
**Arithmetic Logic Unit**. It is responsible for logical operations within the cpu.


What does **FPU** mean and what does it do?
?
**Floating Point Unit**. It is responsible for logical operations that deal with floating point (fractional) numbers within the CPU. It is more specialised than the ALU


What does the **Control Unit** do?
?
It coordinates the actions of the CPU


What are **Registers**?
?
Temporary memory locations
 in the CPU

What is the **Program Counter**?
?
Stores the address to the location in memory of the next instruction.


What is the **Instruction Register**?
?
It stores the instruction currently being executed. It is where the instruction is temporarily stored after it has been fetched from memory.


What is the accumulator?
?
It stores the result of the previous logical CPU operation.
