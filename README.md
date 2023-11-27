# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:RESHMA C 
RegisterNumber: 23012886 
*/
Code:
![image](https://github.com/RESHMA22C/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474426/a616f9fa-e75e-4490-9584-34fdef585ec9)
![image](https://github.com/RESHMA22C/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474426/32cba086-644a-403f-bd5e-d03bec23faeb)

## Output:
![image](https://github.com/RESHMA22C/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474426/f2d43673-3fdf-456d-bb85-6e6394e003a9)
![image](https://github.com/RESHMA22C/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474426/624d9f0b-a75c-4a94-8cb0-13f2e6876b7f)

## Truthtable:
![image](https://github.com/RESHMA22C/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474426/2f5691fc-9356-4af2-b0f7-c982e9e14383)

![image](https://github.com/RESHMA22C/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474426/d6c36754-dba8-4dd8-b43d-61cf872100df)



##  RTL realization:
![image](https://github.com/RESHMA22C/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474426/55963343-7e28-427c-86c7-e3568b3843de)

![image](https://github.com/RESHMA22C/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474426/4e2c6c30-dfec-43ff-bcd7-1d73998f8b6e)


## Timing diagram :

![image](https://github.com/RESHMA22C/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474426/858a3d25-953f-4d6e-8a34-0f1566f37002)

![image](https://github.com/RESHMA22C/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147474426/d23a56ee-f183-49df-904e-ed791f3ff5b0)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
