AIM:

To implement D flipflop using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY

D Flip-Flop

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.

<img width="756" height="346" alt="Screenshot 2025-12-14 214554" src="https://github.com/user-attachments/assets/ddc695fa-6f80-4e94-99b3-65810e7c1fdb" />


This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.

<img width="462" height="183" alt="Screenshot 2025-12-14 214631" src="https://github.com/user-attachments/assets/f779ee6a-f5dd-4be3-bf4d-5cb0617a8439" />


Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D
<img width="491" height="274" alt="Screenshot 2025-12-14 214642" src="https://github.com/user-attachments/assets/9fea09c7-a2fd-47dc-9538-819d33cd1ac1" />


Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.

Procedure


. Start with the Goal

. Use Latches (SR/Gated)

. Connect Data Inputs

. Clock the Latches

. Observe the Rule (Qn+1 = D)

PROGRAM

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by:GOKULAVANI.R

RegisterNumber:25017080 */

RTL LOGIC FOR FLIPFLOPS

TIMING DIGRAMS FOR FLIP FLOPS

RESULTS
