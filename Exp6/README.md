# 8-bit Shift Register: Logical & Rotate Operations

## Overview

This lab exercise demonstrates the implementation of various **shift and rotate operations** using an **8-bit shift register**. These operations are fundamental in digital systems, especially in processors for bit manipulation and arithmetic computations.

---

## Objectives

- To understand different shift and rotate operations
- To implement these operations using an 8-bit shift register
- To observe bit-level data movement using simulation
- To analyze the role of carry in rotation operations

---

## Operations Implemented

The following operations were implemented:

| Operation | Description |
|----------|------------|
| **LR (Logical Right Shift)** | Shifts bits right, inserts 0 at MSB |
| **LS (Logical Left Shift)** | Shifts bits left, inserts 0 at LSB |
| **ARS (Arithmetic Right Shift)** | Preserves MSB (sign bit) while shifting right |
| **ALS (Arithmetic Left Shift)** | Similar to logical left shift, may cause overflow |
| **RR (Rotate Right)** | LSB moves to MSB |
| **RL (Rotate Left)** | MSB moves to LSB |
| **RRC (Rotate Right with Carry)** | LSB goes to carry, carry goes to MSB |
| **RLC (Rotate Left with Carry)** | MSB goes to carry, carry goes to LSB |

---

## Theory

A **shift register** is a sequential circuit made using flip-flops, used for storing and shifting data. In an 8-bit shift register, 8 flip-flops are connected in series to store 8 bits of data.

- **Shift operations** move bits left or right
- **Rotate operations** circulate bits within the register
- **Carry-based rotations** involve an additional carry flag for data transfer

These operations are widely used in:
- Arithmetic operations
- Data conversion
- Bitwise manipulation
- Processor instruction execution

---

## Implementation Details

- **8 D Flip-Flops** used to store 8-bit data  
- **Clock signal** controls shifting  
- **Multiplexers** used to select operation mode  
- **Control lines** determine type of shift/rotation  
- **Carry bit** used for RRC and RLC operations  

---

## Circuit Design

The circuit was designed using a digital logic simulator (e.g., Logisim).  
Each flip-flop represents one bit, and connections between them change based on the selected operation.

*(Add circuit image here if available)*

---

## Observations

- Logical shifts correctly inserted zeros
- Arithmetic right shift preserved the sign bit
- Rotate operations circulated bits properly
- Carry-based rotations correctly updated both carry and register values
- Outputs changed correctly with each clock pulse

---

## Result

All shift and rotate operations were successfully implemented and verified using an 8-bit shift register.

---

## Conclusion

This experiment helped in understanding how different shift and rotate operations work at the hardware level. It demonstrated how simple flip-flop connections can perform complex bit manipulations. These concepts are essential in digital design and computer architecture.

---

## How to Run (Optional)

1. Open the circuit file in Logisim
2. Provide an 8-bit input
3. Select operation using control lines
4. Apply clock pulses
5. Observe output changes

---
