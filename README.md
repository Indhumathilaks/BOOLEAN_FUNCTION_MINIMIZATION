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

Developed by: L INDHUMATHI 24900500
```
module experiment2(A,B,C,D,f1,w,x,y,z,f2);
input A,B,C,D,w,x,y,z;
output f1,f2;
assign f1=((~B&~D)|(~A&B&D)|(A&B&~C));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
**RTL realization**

![Screenshot 2024-11-23 182154](https://github.com/user-attachments/assets/008af603-5096-4c32-980f-8e4e6ff13f6f)


**Output:**

**TRUTH TABLE**

![Screenshot 2024-11-23 190504](https://github.com/user-attachments/assets/676561b7-fcbf-4b57-a8dd-0601f94678c8)



![Screenshot 2024-11-23 190525](https://github.com/user-attachments/assets/777dff37-01b3-413a-84ba-e8115f4416ab)


**RTL**

![Screenshot 2024-11-23 182720](https://github.com/user-attachments/assets/99900f3a-0052-436e-92d4-a95ef5953873)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

