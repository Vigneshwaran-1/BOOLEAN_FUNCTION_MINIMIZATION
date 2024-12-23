# BOOLEAN_FUNCTION_MINIMIZATION

NAME:P.VIGNESHWARAN

REF NO:24900068



**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule



Developed by: RegisterNumber:*/


**RTL realization**
![ex-2 1](https://github.com/user-attachments/assets/7ef9ed58-99e2-4664-ad24-37b82aecba56)


**Output:**

**RTL**
![ex-2 2](https://github.com/user-attachments/assets/cb780c30-c8a9-42c7-80ca-233cfb99697e)


**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

