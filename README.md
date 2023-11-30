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

![Screenshot 2023-11-26 143908](https://github.com/vamsikrishna272005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147477015/779bd6f1-0888-4ae7-ac79-5db19f7a690e)

Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![Screenshot 2023-11-26 150550](https://github.com/vamsikrishna272005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147477015/7af1f718-3e4a-4341-85cb-5759ae037e08)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
![Screenshot 2023-11-26 163847](https://github.com/vamsikrishna272005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147477015/f3c622ed-275b-47a2-a6df-4af4a473d73e)

![Screenshot 2023-11-26 144204](https://github.com/vamsikrishna272005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147477015/fc405dd8-681d-45fc-83c8-8cc9f28670d4)


Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/

## Output:

## Truthtable
![download](https://github.com/vamsikrishna272005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147477015/246e8302-008a-45b2-8c96-06740bcd95a1)
![download](https://github.com/vamsikrishna272005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147477015/9242166e-b40d-4eed-b051-a3c52fc97fdb)



##  RTL realization


## Timing diagram 
![Screenshot 2023-11-26 150532](https://github.com/vamsikrishna272005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147477015/6361b752-0613-40e2-9e17-a6e56e9a1d8a)
![Screenshot 2023-11-26 143851](https://github.com/vamsikrishna272005/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147477015/ba9a31d6-a072-497b-bf9a-4a5080abf90e)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
