# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![393614176-0f7ebfba-6cd6-4b52-9e63-07bf9c633d47](https://github.com/user-attachments/assets/27a1f19d-6a88-4ba6-8d3a-d58f24380282)
![393614248-bc616def-fd35-4964-b99b-22c2b45c5e3f](https://github.com/user-attachments/assets/ab59e5b4-4a8e-453c-898b-1e320a765826)

**Procedure**


Write the detailed procedure here

**Program:**

 
 i)FULL ADDER  
 
 
 
module fa(a,b,cin,sum,carry); 
input a,b,cin; 
output sum,carry; 
assign sum=( (a ^ b)^c); 
assign carry= ( (a & b)| ( cin &(a ^ b )); 
endmodule





ii)FULL SUBTRACTOR

module fs(a,b,difference,borrow);

input a,b,bin;

output difference,borrow;

assign difference= ( (a ^ b)^bin);

assign borrow = ( ( a & b )| ( bin & ((a ^ b )));

endmodule

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 




Developed by:Priyesh.S 



RegisterNumber:24008184

**RTL Schematic**
FULL ADDER

![393616764-9adc55bb-f248-42c7-8aea-c14d72c89a95](https://github.com/user-attachments/assets/88357ff3-05bc-4a34-9ffd-c43e49d8a10f)
FULL SUBTRACTOR
![393616910-48f597ca-058d-4f42-8cc2-59c147996423](https://github.com/user-attachments/assets/49784e7a-70f1-4ce1-825b-85c718131542)

**Output Timing Waveform**FULL ADDER
![393616787-4e1147f7-358e-449f-88a9-b5c2de43b9f2](https://github.com/user-attachments/assets/6a0a926c-e192-495a-82e9-c8ed0e7dfc3d)
FULL SUBTRACTOR
![393616817-6981e672-6d48-4a35-ab40-ec7ca25dcd1d](https://github.com/user-attachments/assets/563c3417-3f1d-4ad9-b7ab-6a5678535f10)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



