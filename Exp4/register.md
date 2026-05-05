#  Experiment 4

## Implementation of SIPO Shift Register using Logisim  

---  

## Objective  

The objective of this experiment is to understand and implement a Serial-In Parallel-Out (SIPO) shift register using Logisim Evolution. The focus is on converting serial data into parallel output using sequential logic circuits.  

---  

## Background Study  

A shift register is a sequential circuit used to store and shift binary data. It consists of flip-flops connected in series and operates based on clock pulses.  

The **Serial-In Parallel-Out (SIPO)** shift register accepts data serially (one bit at a time) and provides the output in parallel form. With each clock pulse, the input data shifts through the flip-flops, and after a few clock cycles, the data becomes available simultaneously at all outputs.  

SIPO registers are commonly used in applications like data conversion, communication systems, and digital data storage where serial data needs to be converted into parallel form.  

Logisim Evolution helps in designing such circuits and observing their behavior in real time using clock signals and input variations.  

---  

## Experiment Description  

In this experiment, a SIPO shift register was designed and simulated using Logisim.  

Multiple flip-flops were connected in series to form the register. A serial input was provided to the first flip-flop, and a clock signal was used to control the shifting operation. With each clock pulse, the input data moved one step forward through the register.  

After a sufficient number of clock cycles, the data appeared at the outputs of all flip-flops simultaneously, producing a parallel output. The circuit behavior was verified by applying different input sequences and observing the outputs.  

---  

## Circuit Diagram  

[SIPO Register Design](https://github.com/HarshitUpadhyay24/ComputerOrganisationAndArchitecture/blob/main/Exp4/register.jpeg)
[D Flip Flop](https://github.com/HarshitUpadhyay24/ComputerOrganisationAndArchitecture/blob/main/Exp4/D_Flip_Flop.jpeg)

---  

## Observations  

The simulation showed that data was successfully shifted through the flip-flops with each clock pulse.  

Initially, the outputs were zero, but as clock pulses were applied, the input bits propagated through the register. After the required number of cycles, all bits were available at the output lines simultaneously.  

The outputs matched the expected results for different input sequences, confirming correct operation of the SIPO shift register.  

---  

## Result  

The SIPO shift register was successfully implemented and verified using Logisim. The circuit correctly converted serial input data into parallel output.  

---  

## Conclusion  

This experiment provided a clear understanding of how serial data can be converted into parallel form using a SIPO shift register. It reinforced the concepts of flip-flops, clock-driven sequential circuits, and data shifting. The use of Logisim made it easier to visualize and verify the behavior of the circuit effectively.  

---  
