# Lab-8: Simple RISC Machine
* Cumulation of Labs 5-7
* Test using assembler in `sas.zip`
    * Provided by UBC CPEN 211 2020W
* Optimized finite state machine
    * Ranked 4th out of 56 passing submissions based on clock frequency and execution time

## Supported Instructions
![Alt text](Images/Instructions1.png?raw=true "Datapath")
![Alt text](Images/Instructions2.png?raw=true "Datapath")
* `Rn`, `Rd`, `Rm` are 3-bit register number specifiers.
* `im8` is an 8-bit immediate operand encoded as part of the instruction.
* `im5` is a 5-bit immediate operand encoded as part of the instruction.
* `<sh_op>` and `sh` are 2-bit immediate operands encoded as part of the instruction.
* `sx(f)` sign extends the immediate value `f` to 16-bits.
* `sh_Rm` is the value of `Rm` after passing through the shifter connected to the Bin input to the ALU.
* `Z`, `V`, and `N` are the zero, overflow and negative flags of the status register 
* `status` refers to all three of `Z`, `V`, and `N`.
* `R[x]` refers to the 16-bit value stored in register x.
* `M[x]` is the 16-bit value stored in main memory at address x.
* `PC` refers to the program counter register.
* `<label>` refers to a textual marker in the assembly that indicates an instruction address
