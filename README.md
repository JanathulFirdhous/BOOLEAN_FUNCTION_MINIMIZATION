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
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Janathul Firdhous
RegisterNumber:24900115



**RTL realization**

![Screenshot (43)](https://github.com/user-attachments/assets/bc7e1ad6-13c8-476f-9b28-1d0af8b41c87)


**Output:**


**Timing Diagram**

![Screenshot 2024-11-25 203846](https://github.com/user-attachments/assets/eca09aa3-ba97-4f5d-9b40-6521d07aea76)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

