# BOOLEAN_FUNCTION_MINIMIZATION

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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

module exp2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

Developed by:R Dinesh Karthick
RegisterNumber:25018555


**RTL realization**
**RTL**
<img width="1338" height="839" alt="image" src="https://github.com/user-attachments/assets/f8a03655-9aed-4f14-a973-911d923226f4" />



**Output:**
**Timing Diagram**

<img width="1914" height="568" alt="image" src="https://github.com/user-attachments/assets/18b8f399-d3f7-4188-9d7c-a78ba636a1b5" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

