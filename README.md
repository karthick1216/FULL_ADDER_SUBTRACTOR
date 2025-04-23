*Date : 23/04/25
*AIM:*

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

*Equipments Required:*

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

*Full Adder and Full Subtractor*
```
Developed by : Karthick . S
Register no : 212224230114
```

*Full Adder*

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

*Figure -1 FULL ADDER*

*Full Subtractor*

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

*Truthtable*

*full adder*

![WhatsApp Image 2025-04-22 at 21 54 06_bd25fa93](https://github.com/user-attachments/assets/b793b19d-7f46-4130-9c95-a9d6158c8ee7)

*full subractor*

![WhatsApp Image 2025-04-22 at 21 55 21_f700f028](https://github.com/user-attachments/assets/06ded534-36ba-4681-9d9c-aa9341c1da3e)

*Procedure*

Write the detailed procedure here

*Program:*

*full adder*

![image](https://github.com/user-attachments/assets/56dd238d-e638-45f9-825f-697fd2cb30b8)

*full subractor*

![image](https://github.com/user-attachments/assets/b86a0d22-6bb8-41a3-bc20-f9833eea7368)

*RTL Schematic*

*full adder*

![WhatsApp Image 2025-04-22 at 21 45 03_8f229122](https://github.com/user-attachments/assets/e8b08da0-cf3f-4d9a-a6d5-f269beb0af12)


*full subractor*

![WhatsApp Image 2025-04-22 at 21 45 43_ca399260](https://github.com/user-attachments/assets/4d8280b0-3928-4666-a2ad-0e73fcb45888)

*Output Timing Waveform*

*full adder*

![WhatsApp Image 2025-04-22 at 21 48 54_8898bc05](https://github.com/user-attachments/assets/f77ebd2d-fc3a-4c1a-bfc6-193f9627cbb2)

*full subractor*

![WhatsApp Image 2025-04-22 at 21 49 21_8ce48182](https://github.com/user-attachments/assets/ffc563c6-1509-45a1-bedc-74ae42f51a9b)

*Result:*

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.
