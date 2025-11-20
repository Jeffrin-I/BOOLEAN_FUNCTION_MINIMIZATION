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

Developed by: Jeffrin I
RegisterNumber: 25009198


**RTL realization**

![pro-1_page-0001 (1)](https://github.com/user-attachments/assets/432412a1-1d36-4798-a486-7b656097fd07)

**Output:**

**RTL**
![Dp-2_page-0001](https://github.com/user-attachments/assets/5d392ce3-62f9-4590-9c0f-67d3fd79c8d8)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

