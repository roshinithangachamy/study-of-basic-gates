### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

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

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by: RegisterNumber:212223230175 
 
**Logic symbol & Truthtable**


**RTL realization Output:** 
AND GATE:
![ANDGATE](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/2050a883-4510-4133-b6d4-6aeb68be4d55)

OR GATE:
![ORGATE](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/5cd79c65-0ab9-4120-9bd8-bab602b785ec)

NAND GATE:
![NANDGATE](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/6cbf99d6-88a0-4e2c-a4ff-7c75b6831d5a)


**RTL**
AND GATE:
![RTL](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/427c371e-9f91-4baa-a006-6b2f1c51bfa5)

OR GATE:
![OR](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/042177cc-0176-4887-a0b6-9e4bee1fdac8)

NAND GATE:
![NANDGATE](https://github.com/roshinithangachamy/study-of-basic-gates/assets/147118341/574bfbe6-573d-4a8e-8c7c-0e735a184b65)

**Result:**


