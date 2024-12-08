# BOOLEAN_FUNCTION_MINIMIZATION

## AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

## Equipment Required:

Hardware – PCs, Cyclone II , USB flasher

## Software – Quartus prime

## Theory
## Logic Diagram

## Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## Program:

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
### module funct1(a,b,c,d,f1);
### input a,b,c,d;
### output f1;
### assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
### endmodule

### module funct2(w,x,y,z,f2);
### input w,x,y,z;
### output f2;
### assign f2=((~y&z)|(w&y)|(x&y));
### endmodule

Developed by: Infant Maria Stefanie .F
RegisterNumber:24001512


## RTL realization

## Output:

![Screenshot 2024-12-08 152936](https://github.com/user-attachments/assets/40de57d2-a72f-458e-833e-a2b93659c787)

![Screenshot 2024-12-08 152943](https://github.com/user-attachments/assets/7767e0f4-336b-458f-a511-8bbfc9453ea9)


## RTL

## Timing Diagram
![Screenshot 2024-12-08 152956](https://github.com/user-attachments/assets/6ad02297-5be5-4350-b4f3-a04221c3d99a)


## Result:

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

