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

 * Instruction Set Supported:
        <details>
           <summary>Instruction Set Supported</summary>
           <p>| Opcode |     R1    |    R2    | 
              |--------|-----------|----------|
              | 4 bits |   6 bits  |  6 bits  |</p>
         </details>