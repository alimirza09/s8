# s8

A custom 8bit CPU with custom instruction set.

## Instruction Set

* 0x0. MW
* 0x1. LW
* 0x2. SW
* 0x3. ADD
* 0x4. ADC
* 0x5. SB
* 0x6. SBC
* 0x7. PUSH
* 0x8. POP
* 0x9. AND
* 0xA. OR
* 0xB. NOR
* 0xC. CMP
* 0xD. OUTB
* 0xE. INB
* 0xF. JNZ

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
