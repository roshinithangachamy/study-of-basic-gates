### study-of-basic-gates

Developed by: RegisterNumber:212223230175 
 

## AIM: 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

## Equipments Required:

Software – Quartus prime 

## Theory

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

## AND gate

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

## OR gate 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

## NOT gate

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

## NAND gate

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

## NOR gate

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

## Ex-OR gate

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

## Ex-NOR gate

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

## Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## PROGRAM

AND GATE:
```
module andgate(a,b,c);
  input a;
  input b;
  output c;
  assign c = a & b;
endmodule 
```
OR GATE:
```
module orgate(a,b,d);
  input a;
  input b;
  output d;
  assign d = a | b;
endmodule
```
NAND GATE:
```
module nandgate(a,b,e);
  input a;
  input b;
  output e;
  assign e = ~(a & b);
endmodule
```
NOT GATE:
```
module not12(a,g);
  input a;
  output g;
  assign g = ~a;
endmodule
```
NOR GATE:
```
module nor12(a,b,f);
 input a;
 input b;
 output f;
 assign f = ~(a | b);
endmodule
```
 
## Logic symbol & Truthtable

## and symbol:
![AND](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/3cb71959-3c68-4efd-89b4-4c440b4ae32f)


## or symbol:
![OR](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/67898d45-e76f-4872-a698-33610cd0c2ff)

## nand symbol:
![NAND](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/94488fac-a20d-4ac1-b688-6150a79a7e9a)

## not symbol:
![NOT](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/b3d0d4d1-b385-48b6-8ed8-b07f3216bab5)

## RTL realization Output

AND GATE
![ANDGATE](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/2050a883-4510-4133-b6d4-6aeb68be4d55)

OR GATE
![ORGATE](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/5cd79c65-0ab9-4120-9bd8-bab602b785ec)

NAND GATE
![NANDGATE](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/6cbf99d6-88a0-4e2c-a4ff-7c75b6831d5a)

NOT GATE
![NANDGATE](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/25b8e4f1-7ce1-4ee7-a1fd-ed00cb261257)

## RTL 

## Result:


