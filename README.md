# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:A.ViMAL 
RegisterNumber:*24005922/

**RTL Schematic**
![WhatsApp Image 2024-12-02 at 20 36 50_7ee21266](https://github.com/user-attachments/assets/7d9cfbef-3c11-41e2-b53e-854fd74f0c7b)
![WhatsApp Image 2024-12-02 at 20 36 50_cf5d3d81](https://github.com/user-attachments/assets/a320379c-dae3-4d98-9812-057a2d99ea4a)


**Output/TIMING Waveform**
![WhatsApp Image 2024-12-02 at 20 36 50_cff3b97e](https://github.com/user-attachments/assets/3e225521-07c9-4e93-8486-c94d7e7e4e60)
![WhatsApp Image 2024-12-02 at 20 36 51_78925be7](https://github.com/user-attachments/assets/df08f903-54b4-4591-9f07-770f2158bd23)


**Result:**
To calculate the result for a given set of inputs 
𝐴
A, 
𝐵
B, and 
𝑀
M (Mode: 
𝑀
=
0
M=0 for addition, 
𝑀
=
1
M=1 for subtraction), let's break it down systematically.
