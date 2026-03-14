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

module combinationalcircuit(A,B,C,D,F1); input A,B,C,D; output F1; wire x1,x2,x3,x4,x5; assign x1=(~A)&(~B)&(~C)&(~D); assign x2=(A)&(~C)&(~D); assign x3=(~B)&(C)&(~D); assign x4=(~A)&(B)&(C)&(D); assign x5=(B)&(~C)&(D); assign F1=x1|x2|x3|x4|x5; endmodule

Developed by:Rahul Krishna RegisterNumber:212223040162 */


**RTL realization**


**Output:**

**RTL**
![Screenshot 2024-04-03 095914](https://github.com/RahulKrishna05/BOOLEAN_FUNCTION_MINIMIZATION/assets/162027231/4933ff88-df8f-4dd9-88ec-8089668582c6)

**Truth Table**

![Screenshot 2024-04-03 095928](https://github.com/RahulKrishna05/BOOLEAN_FUNCTION_MINIMIZATION/assets/162027231/4eb2a3f7-f3db-416e-92fd-f90a0792ba2b)


**Timing Diagram**
![Screenshot 2024-04-03 095947](https://github.com/RahulKrishna05/BOOLEAN_FUNCTION_MINIMIZATION/assets/162027231/0a954f03-bc3b-4072-abe4-629274192fa3)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

