**NAME: DHASHVANTH B**


**REG NO:24900063**

# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Full Adder**


<img width="370" alt="Screenshot 2024-12-12 at 10 56 38 AM" src="https://github.com/user-attachments/assets/931b8738-65c5-4d10-b5b7-6df43266e044" />

**Full Subtractor**


<img width="379" alt="Screenshot 2024-12-12 at 10 56 57 AM" src="https://github.com/user-attachments/assets/80c801fb-3c63-451a-93a8-ee5b64df57cd" />


**Procedure**

**Full Adder**

1.Open Quartus II and create a new project. 

2.Use schematic design entry to draw the full adder circuit. 

3.The circuit consists of XOR, AND, and OR gates. 

4.Compile the design, verify its functionality through simulation. 

5.Implement the design on the target device and program it.

**Full Subtractor**

1.Follow the same steps as for the full adder. 

2.Draw the full subtractor circuit using schematic design. 

3.The circuit includes XOR, AND, OR gates to perform subtraction. 

4.Compile, simulate, implement, and program the design similarly to the full adder.

**Program:**


<img width="510" alt="Screenshot 2024-12-12 at 10 57 59 AM" src="https://github.com/user-attachments/assets/e403f774-68eb-4521-9ead-2dd0990cbbbb" />

**RTL VIEWER**


<img width="606" alt="Screenshot 2024-12-12 at 10 58 21 AM" src="https://github.com/user-attachments/assets/60afb5a5-c2d7-446e-9046-fe5cce4ac947" />

**OUTPUT TIMING WAVEFORM**


<img width="652" alt="Screenshot 2024-12-12 at 10 58 44 AM" src="https://github.com/user-attachments/assets/4a480372-bab1-4df8-9c83-e42e96d08c80" />


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified in Quartus software using verilog program.




