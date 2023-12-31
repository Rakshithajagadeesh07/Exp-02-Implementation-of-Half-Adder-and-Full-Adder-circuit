# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime
## Theory:
Adders are digital circuits that carry out addition of numbers.

## Half Adder:
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

## Full Adder:
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)
## Figure -01 HALF ADDER:

![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)
## Figure -02 FULL ADDER:

## Procedure:
Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.

## Program:
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: RAKSHITHA J

RegisterNumber: 212223240135
## Code:
HALF ADDER:

![Exp3 ha code](https://github.com/Rakshithajagadeesh07/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147081797/d596b0e5-da4d-46e2-bb1a-b691b667ac26)

FULL ADDER:

![Exp3 fa code](https://github.com/Rakshithajagadeesh07/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147081797/3f9fd161-2a56-4c07-b1a4-b00377c1ef6d)

## RTL realization:
HALF ADDER:

![Exp3 ha RTL diagram](https://github.com/Rakshithajagadeesh07/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147081797/5da961ec-ef5a-40b6-a9c4-cb6d1af7cd0e)

FULL ADDER:

![Exp3 fa RTL diagram](https://github.com/Rakshithajagadeesh07/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147081797/4e06bc57-e63a-4d70-b22a-9189e47b5a56)

## Truth Table:
HALF ADDER:

![Exp3 truthtable (ha)](https://github.com/Rakshithajagadeesh07/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147081797/7cacfc44-b096-44eb-b95b-268f10a59e62)

FULL ADDER:

![Exp3 truthtable (fa)](https://github.com/Rakshithajagadeesh07/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147081797/a5458b4b-bc39-4291-b0e8-e722a7dddf83)

## Timing diagram:
HALF ADDER:
![halfadder wf 1](https://github.com/Rakshithajagadeesh07/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147081797/b6d6c308-4ac5-4849-b055-1f8c5374e135)
FULL ADDER:
![fulladder wf 1](https://github.com/Rakshithajagadeesh07/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147081797/cdf9d761-91bd-4e33-9f39-dc8bfe45467e)

## Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog programming.
