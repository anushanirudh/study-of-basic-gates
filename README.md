### EX 01             STUDY-OF-BASIC-GATES

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

**AND GATE**

**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming
Developed by: R Anirudh RegisterNumber: 212223230016


![Screenshot 2024-04-10 212707](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/d1d0e583-e27a-4135-902d-85353eff374a)

 
**Logic symbol & Truthtable**

![Screenshot 2024-04-10 212748](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/e0eb2c05-50f5-46a9-b3fc-0447f4037cb0)


**RTL realization:** 

![Screenshot 2024-04-10 212837](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/db1898bc-af9f-44cb-b9b9-43c016c932db)


**Output:**

![Screenshot 2024-04-10 212909](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/fecd27f8-7b14-418d-a03f-d9f55eeead16)

**OR GATE**

**PROGRAM**

![Screenshot 2024-04-10 213023](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/fa4853f4-c816-4f97-be86-78e0b71c6b1d)

**Logic symbol & Truthtable**

![Screenshot 2024-04-10 213117](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/8ca1ed82-92f7-4515-9d78-b93fe7af4c2a)

**RTL realization:** 

![Screenshot 2024-04-10 213213](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/017acbc7-3679-4307-a1ea-d9b720ee2c9f)

**Output:**

![Screenshot 2024-04-10 213306](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/c5251523-0015-411f-9558-6b9248652f9c)

**NOT GATE**

**PROGRAM**

![Screenshot 2024-04-10 213740](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/1b21fc00-a303-4729-8279-01d514e21715)

**Logic symbol & Truthtable**

![Screenshot 2024-04-10 213823](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/1202273b-8e77-4348-821d-02332f0ebbd0)

**RTL realization:** 

![Screenshot 2024-04-10 213909](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/50a4e737-9ef9-4a02-9f1c-d05654e2cb5e)


**Output:**

![Screenshot 2024-04-10 213948](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/3265f736-e476-4de5-9ff1-ddffc2f45f2f)

**NAND GATE**

**PROGRAM**

![Screenshot 2024-04-10 213426](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/f49b1e95-2a3a-4651-bd13-63a70c8a5dab)

**Logic symbol & Truthtable**

![Screenshot 2024-04-10 213508](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/0726621b-04cf-42ce-b217-0f75541ffcd8)

**RTL realization:** 

![Screenshot 2024-04-10 213536](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/7ac4d40d-7c5a-441f-aafa-b6738bc253a2)

**Output:**

![Screenshot 2024-04-10 213615](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/4ae210a3-af8a-4f13-aeca-7a6724a6420c)

**NOR GATE**

**PROGRAM**

![Screenshot 2024-04-10 214059](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/19af4975-b794-4002-823d-8c2fad093adb)

**Logic symbol & Truthtable**

![Screenshot 2024-04-10 214140](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/2d724239-1d26-4138-a452-c83cfe667ccb)

**RTL realization:** 

![Screenshot 2024-04-10 214212](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/8fe49bf9-ee33-46b3-b683-cb82750ad0aa)

**Output:**

![Screenshot 2024-04-10 214246](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/054ad962-ae5c-4773-a38f-6bcdbc253599)

**EX-OR GATE**

**PROGRAM**

![Screenshot 2024-04-10 214340](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/f8598a46-4e99-47c0-ba2a-b0c0ce6c6310)

**Logic symbol & Truthtable**

![Screenshot 2024-04-10 214411](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/59525516-b24f-4941-b68f-f0115c91fddb)

**RTL realization:** 

![Screenshot 2024-04-10 214500](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/7b5abee6-679c-43e9-9f0a-77bf581695f0)

**Output:**

![Screenshot 2024-04-10 214546](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/644b4fc5-de50-463a-b26a-9a1fa9bfd235)


**EX-NOR GATE**

**PROGRAM**

![Screenshot 2024-04-10 214638](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/15bdc09c-f62b-4ff1-9567-6b40d12b591f)

**Logic symbol & Truthtable**

![Screenshot 2024-04-10 214725](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/be058615-b2ae-4de7-a1ed-c471f1c1c22d)

**RTL realization:** 

![Screenshot 2024-04-10 214802](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/627d31db-ed9f-4a3f-90fa-e925cb491d72)

**Output:**

![Screenshot 2024-04-10 214851](https://github.com/anushanirudh/study-of-basic-gates/assets/151725737/691e5ef4-2818-4a9d-8f9c-224faa28b5d9)


**Result:**
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.



