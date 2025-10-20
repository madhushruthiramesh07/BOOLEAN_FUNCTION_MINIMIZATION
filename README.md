# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

f1
```
module funct1(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule
```

f2
```
module funct2(w,x,y,z,f2); 
input w,x,y,z; 
output f2; 
assign f2=((~y & z)|( w & y )|(x & y)); 
endmodule
```

Developed by: RegisterNumber:25008368


**RTL realization**
logic diagram f1
<img width="1920" height="1080" alt="Screenshot 2025-10-09 224329" src="https://github.com/user-attachments/assets/e149e8d8-3aa7-405a-b729-9c1c4d1fc3c1" />


wave form f1

<img width="1920" height="1080" alt="Screenshot 2025-10-09 224713" src="https://github.com/user-attachments/assets/fa4ab791-e0d9-4c87-bf41-1d6023d67eb4" />


**Output:**

**RTL**
logic diagram f2
<img width="1265" height="704" alt="Screenshot 2025-10-09 230423" src="https://github.com/user-attachments/assets/a2b7d957-2faa-4a95-9176-7df3d0566531" />

waveform f2
<img width="1920" height="1080" alt="Screenshot 2025-10-09 230639" src="https://github.com/user-attachments/assets/cdad8fb5-6e70-4af7-a9be-444bb1a45874" />




**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

