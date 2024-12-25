### NAME: PRIYESH .S
### REF NO: 24008181
## AIM

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

## Full Adder and Full Subtractor

## Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’C+ A’BC’ + ABC + AB’C’ = A ⊕ B ⊕ C

Carry = (A⊕B)C + AB

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

## Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ C 

Borrow = (A ⊕ B)'C + A'B


## Procedure
    **Full Adder:**
    1.Open Quartus II and create a new project.
    2.Use schematic design entry to draw the full adder circuit. 
    3.The circuit consists of XOR, AND, and OR gates. 
    4.Compile the design, verify its functionality through simulation. 
    5.Implement the design on the target device and program it.
    
    **Full Subtractor:** 
    1.Follow the same steps as for the full adder. 
    2.Draw the full subtractor circuit using schematic design. 
    3.The circuit includes XOR, AND, OR gates to perform subtraction. 
    4.Compile, simulate, implement, and program the design similarly to the full adder.



## Program
![Screenshot 2024-11-28 141427](https://github.com/user-attachments/assets/6dcd78cf-5cc5-46cb-aae9-fbeae8e7eeb7)

## Logic Symbol and Truthtable
#### Full Adder:
![Screenshot 2024-11-28 200627](https://github.com/user-attachments/assets/75afe26c-7485-4665-b9df-1092b3e61cc2)
#### Full subtractor:
![Screenshot 2024-11-28 205620](https://github.com/user-attachments/assets/f8635e07-0149-442a-8985-d06db4979f03)


## RTL output
![Screenshot 2024-11-28 141503](https://github.com/user-attachments/assets/ae8ab8a2-8c4c-4418-8401-61caa20bfc51)

## Output Timing Waveform*
![Screenshot 2024-11-28 142000](https://github.com/user-attachments/assets/64ca27da-1fed-482a-8b0f-c9dd7b00274b)


## Result

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.






