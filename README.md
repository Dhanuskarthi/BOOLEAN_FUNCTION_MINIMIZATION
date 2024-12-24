# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**
![IMG-20241014-WA0025 1](https://github.com/user-attachments/assets/7937c32c-6c5b-4be0-bf28-d48d2af093a1)

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
module exp2-1(a,b,c,d,f1);
input a,b,cd;
output f1;
assign f1=((~B&~D)|(~A&B&D)|(A&B&~C));
endmodule module exp2-2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
 /* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by: RegisterNumber:*/24005701


**RTL realization**
![exp22](https://github.com/user-attachments/assets/95bb2340-574f-41a7-b427-548a1ba24d6a)
![exp2](https://github.com/user-attachments/assets/6cbb5afe-2e54-4d6f-ba57-850922302fa0)


**Timing Diagram**
![exp22](https://github.com/user-attachments/assets/319ed8da-1018-4745-83d7-28b7189ae155)
![exp2](https://github.com/user-attachments/assets/ffe6d8e8-58a1-4929-b0af-206e67a98e0e)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

