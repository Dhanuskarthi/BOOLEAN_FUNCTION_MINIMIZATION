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
module exp2-1(a,b,c,d,f1); input a,b,cd; output f1; assign f1=((~B&~D)|(~A&B&D)|(A&B&~C)); endmodule module exp2-2(w,x,y,z,f2); input w,x,y,z; output f2; assign f2=((~y&z)|(x&y)|(w&y)); endmodule /* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by: RegisterNumber:*/24005701


**RTL realization**

![exp22](https://github.com/user-attachments/assets/0cd3836d-5362-4789-a2ee-23f83e005f29)

![exp2](https://github.com/user-attachments/assets/c3f9bca9-15b6-4ed8-9268-82a8ab231499)

**Timing Diagram**

![exp2](https://github.com/user-attachments/assets/70641dd5-b15a-44fc-83a3-76dea1d2a008)

![exp22](https://github.com/user-attachments/assets/30c4af06-e01c-4c99-93fc-b016750a19c1)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

