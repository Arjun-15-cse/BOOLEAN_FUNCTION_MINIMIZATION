**EXP2:BOOLEAN FUNCTION MINIMIZATION**

NAME: ARJUN.K

REFERENCE NO: 24900977

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

**RTL realization**

![WhatsApp Image 2024-12-04 at 16 07 17_4a420d05](https://github.com/user-attachments/assets/cac943f8-1c15-41d9-84e2-431abe7ee2b0)


**RTL**

![WhatsApp Image 2024-12-04 at 16 06 28_280e3c21](https://github.com/user-attachments/assets/110704bb-4381-4aa3-997a-6557c99b6606)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

