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

/* write all the steps invloved */

**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

<img width="761" height="330" alt="image" src="https://github.com/user-attachments/assets/8abcf52c-7c28-4962-903b-434f656af970" />

 Developed by:MADHU.P   RegisterNumber:25012991


**RTL LOGIC FOR 4 Bit Ripple Counter**

<img width="977" height="468" alt="image" src="https://github.com/user-attachments/assets/fe875245-9246-4ee4-8a2b-a7eed6879db1" />

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

<img width="1597" height="222" alt="image" src="https://github.com/user-attachments/assets/a039f7c3-f9fe-4f0a-b97b-1e143f054c5b" />
**RESULTS**


Thus 4 Bit Ripple Counter has been implemented using verilog and validated their functionality using their functional tables
