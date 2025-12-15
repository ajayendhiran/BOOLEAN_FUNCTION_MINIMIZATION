# BOOLEAN_FUNCTION_MINIMIZATION
**Date:15/12/2025**

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
```
module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule
```
Developed by:Jeyandhiran RegisterNumber:25017257 */




**Output:**
<img width="1520" height="828" alt="image" src="https://github.com/user-attachments/assets/f97ce227-3b72-48ba-a9ff-4a6a1b1b651c" />
**RTL realization**
**RTL**
<img width="1012" height="261" alt="image" src="https://github.com/user-attachments/assets/63943a45-385b-4167-b92a-b1e8bfa365d1" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

