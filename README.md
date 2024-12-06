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

Developed by: VINUTHAA NN

RegisterNumber:24900700

```
emodule experiment2(A,B,C,D,f1,w,x,y,z,f2);
input A,B,C,D,w,x,y,z;
output f1,f2;
assign f1=((~B&~D)|(~A&B&D)|(A&B&~C));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

**RTL realization**

![Screenshot 2024-12-06 113613](https://github.com/user-attachments/assets/319d5246-0b65-4744-8c1a-75fb36426192)


**Output:**

![Screenshot 2024-12-06 113634](https://github.com/user-attachments/assets/c138d57c-595f-42f3-9015-b09c8faa3d45)

![Screenshot 2024-12-06 113645](https://github.com/user-attachments/assets/01dca20d-f14f-44b6-88d3-0b63a55e6648)

**RTL**

![Screenshot 2024-12-06 113700](https://github.com/user-attachments/assets/3fe80412-d07e-4c2d-9443-5f01919bea4e)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.



Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

