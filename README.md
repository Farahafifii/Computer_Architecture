## Description 

This is a simulation of a fictional processor design and architecture (Harvard Architecture) using Java

## Memory Structure 

A Harvard Architecture in which the Instruction data and Program Data are stored in two different memories `Data Memory size is 2048 rows,8 bits/row while Instruction Memory size is 1024 16 bits/row `

## Registers 
 * 64 General Purpose Registers 8 bits/Register
 * 1 Status Register `contains the flags : Carry, Overflow, Negative, Sign, Zero`
 * Program Counter size :16 bits

## Instruction Set Architecture
 * Instruction Size : 16 bits 
 * Intruction Types : 
     * R-Type:

         | Opcode |     R1    |    R2    | 
         |--------|-----------|----------|
         | 4 bits |   6 bits  |  6 bits  |

     * I- Type :
         | Opcode |     R1    |Immeadiate| 
         |--------|-----------|----------|
         | 4 bits |   6 bits  |  6 bits  |

 * Instruction Set Supported
         
    | Name |     Format    |Operation            | 
    |----|---|--- |
    | ADD |   ADD R1 R2  |  R1 = R1+R2           |
    | SUB |   SUB R1 R2  |  R1 = R1-R2           |
    | MUL |   MUL R1 R2  |  R1 = R1*R2           |
    | LDI |   LDI R1 IMM |  R1 = IMM             |
    | BEQZ|  BEQZ R1 IMM |  IF (R1==0){ PC = PC+1 + IMM}   |
    | AND |   AND R1 R2  |  R1 = R1&R2   |
    | OR |   OR R1 R2  |  R1 = R1 |\ R2   |
    | JR |   JR R1 R2  |  PC = R1 |\|\R2  |
    | OR |   OR R1 R2  |  R1 = R1 | R2   |
         