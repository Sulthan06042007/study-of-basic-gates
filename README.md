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
```
Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by:A Mohamed Sulthan
 RegisterNumber: 212223230125
```
 ### PROGRAM
 
 ![312524418-91cd9c06-dc03-4c8c-9aca-5f9e3eab0189](https://github.com/prithviraj5703/study-of-basic-gates/assets/121418418/a1434626-9473-4894-a0be-ff934bf9c76b)

 
## Logic symbol & Truthtable:
![312524944-f9705d15-097d-41f0-938e-727ac8c817fe](https://github.com/prithviraj5703/study-of-basic-gates/assets/121418418/e7f4b97c-18da-450e-9833-8e0113930829)


## RTL realization :
![312525416-523d3d1f-416e-46fc-b087-8e2e92053a69](https://github.com/prithviraj5703/study-of-basic-gates/assets/121418418/bd0fa301-0c54-463f-b09c-01b805438343)


## RTL OUTPUT:
![312525723-f207de9e-70e8-480c-805b-7bba6eba26d7](https://github.com/prithviraj5703/study-of-basic-gates/assets/121418418/bb7b6deb-5881-4bc6-a6b7-c0016c08fae5)


## Result:
```
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.
```

