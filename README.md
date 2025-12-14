AIM:

To implement D flipflop using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY

D Flip-Flop

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.
<img width="648" height="331" alt="image" src="https://github.com/user-attachments/assets/c0f6606c-8177-4c4b-b017-0f645d5a77f8" />


image

This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.
<img width="372" height="139" alt="image" src="https://github.com/user-attachments/assets/5c260aa7-ba55-4de9-a376-de5670b7656c" />


image

Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D
<img width="383" height="203" alt="image" src="https://github.com/user-attachments/assets/3f2f449a-0ad7-4f58-b866-7e2d00236276" />


image

Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.

Procedure

/* write all the steps invloved */

PROGRAM

/* Program for flipflops and verify its truth table in quartus using Verilog programming.
Developed by:R.AISHWARYA
RegisterNumber: 25017062

RTL LOGIC FOR FLIPFLOPS

TIMING DIGRAMS FOR FLIP FLOPS

RESULTS
