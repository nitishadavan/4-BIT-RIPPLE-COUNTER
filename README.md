# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

1.Type the program in Quartus software.
2.Compile and run the program.
3.Generate the RTL schematic and save the logic diagram.
4.Create nodes for inputs and outputs to generate the timing diagram.
5.For different input combinations generate the timing diagram.

**PROGRAM**

![Screenshot 2024-12-23 114848](https://github.com/user-attachments/assets/779e2495-3451-4508-bd80-e584ef0889e0)


/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by:D.Nitish Adavan
 
 RegisterNumber:24901049
*/

**RTL LOGIC FOR 4 Bit Ripple Counter**

![Screenshot 2024-12-23 114901](https://github.com/user-attachments/assets/b5da194f-5625-4501-9308-179583650e59)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![Screenshot 2024-12-23 114914](https://github.com/user-attachments/assets/95477b89-02fc-4cbc-b401-659e757b1c06)


**RESULTS**

Thus, the Ripple-Counter is designed, and its functionality is validated using the
truth table and timing diagrams.
