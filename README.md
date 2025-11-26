# s8

A custom 8bit CPU with custom instruction set.

## Instruction Set

0. MW
1. LW
2. SW
3. ADD
4. ADC
5. SB
6. SBC
7. PUSH
8. POP
9. AND
* A. OR
* B. NOR
* C. CMP
* D. OUTB
* E. INB
* F. JNZ

## Registers

* A (0): GP register
* B (1): GP register
* C (2): GP register
* D (3): GP register
* L (4): GP register/(L)ow index register
* H (5): GP register/(H)igh index register
* X (6): GP register
* Z (7): GP register
* F (7): flags (LSB to MSB)
    * LESS
    * EQUAL
    * CARRY
    * BORROW

### Calling Convention

A,B,C and D for arguments
X for return value
