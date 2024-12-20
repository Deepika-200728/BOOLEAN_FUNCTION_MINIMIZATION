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
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:DEEPIKA.R
RegisterNumber:24900696
*/


**RTL realization**

![Screenshot (20)](https://github.com/user-attachments/assets/a34f18d7-a474-4396-8c7e-7b48eadd1c32)
![Screenshot (24)](https://github.com/user-attachments/assets/3722c534-c3ff-43ea-8fad-b17e7aeb7d4f)

**Timing Diagram**

![Screenshot (21)](https://github.com/user-attachments/assets/ef911650-816d-4979-88a3-d1be6227a674)
![Screenshot (25)](https://github.com/user-attachments/assets/f1060dd2-6c59-4452-a2a4-3037a434c2dc)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

