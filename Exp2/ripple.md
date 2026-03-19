# Experiment 2

## Implementation of Ripple Carry Adder using Basic Logic Gates in Logisim

---

## Objective

The objective of this experiment is to design and implement a Ripple Carry Adder using basic logic gates (AND, OR, and NOT) in Logisim Evolution. The aim is to understand binary addition and carry propagation across multiple stages.

---

## Background Study

A Ripple Carry Adder is a combinational circuit used to perform binary addition of multi-bit numbers. It is constructed by connecting multiple full adders in series. The carry output of each stage is passed to the next stage, resulting in a ripple effect.

A full adder is built using basic logic gates such as AND, OR, and NOT. It takes three inputs: two bits and a carry-in, and produces a sum and carry-out.

The main limitation of a ripple carry adder is propagation delay, as each stage must wait for the carry from the previous stage. However, it is simple and easy to design.

Logisim Evolution is a digital circuit simulator that helps in designing and visualizing such circuits effectively.

---

## Experiment Description

In this experiment, a ripple carry adder was designed using only AND, OR, and NOT gates in Logisim.

First, a full adder circuit was implemented using basic gates. Then, multiple full adders were connected in sequence to form a multi-bit ripple carry adder (e.g., 4-bit).

The carry-out of each stage was connected to the carry-in of the next stage. Different input combinations were tested, and outputs were verified by observing the sum and carry values.

---

## Circuit Diagram

[Ripple Carry Adder using Basic Gates](#)

---

## Observations

The ripple carry adder correctly performed binary addition for all input combinations. The carry propagated sequentially from one stage to another.

It was observed that as the number of bits increased, the delay also increased due to carry propagation through each stage.

---

## Result

The ripple carry adder was successfully implemented using basic logic gates in Logisim. The outputs matched the expected results for all test cases.

---

## Conclusion

This experiment helped in understanding the working of ripple carry adders and carry propagation. It demonstrated how complex circuits can be built using basic logic gates and highlighted the limitation of propagation delay in such designs.
