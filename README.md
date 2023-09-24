# Full Adder Schematic and Layout Design using Cadence
## Problem Statement
+ Design a full adder using Convention CMOS logic and Mirror Circuit Concept.
+ Use all MOS devices with W/L ratio of 400n/180n. 
+ Design the layout for the Mirror circuit using Minimum area.

## Introduction
+ Full adder is a combinational logic circuit which is used for the purpose of adding three inputs and produces two outputs. 
+ Full adders are implemented with logic gates in hardware.
+ It adds three one-bit binary numbers, two operands and a carry bit, and it outputs two numbers, a sum and a carry bit.

## Truth Table
<p align="center">
<img width="211" alt="image" src="https://github.com/Veda1809/Layout_Design/assets/142098395/93c8c5ac-de4a-42eb-a3b4-8d2d197322d7">
</p>
<p align="center">
  Fig 1.
</p>

+ **SUM = A’B’Cin + A’BCin’ + AB’Cin’ + ABCin**
+ **CARRY = AB + ACin + BCin**

## Logic Gate Diagram
<p align="center">
<img width="232" alt="image" src="https://github.com/Veda1809/Layout_Design/assets/142098395/3cc3bd1a-7061-405c-a095-ff3ef6f949f9">
</p>
<p align="center">
Fig 2.
</p>

## Conventional Circuit Schematic
<p align="center">
<img width="495" alt="image" src="https://github.com/Veda1809/Layout_Design/assets/142098395/508fe0de-cb56-4406-a7eb-bddf075091a4">
</p>
<p align="center">
Fig 3.
</p>

## Mirror Circuit Schematic
<p align="center">
<img width="500" alt="image" src="https://github.com/Veda1809/Layout_Design/assets/142098395/d47bc7b9-6949-4a6d-af50-751fbddf3c24">
</p>
<p align="center">
Fig 4.
</p>

## Mirror Circuit Symbol
<p align="center">
<img width="494" alt="image" src="https://github.com/Veda1809/Layout_Design/assets/142098395/da327c1d-c724-4bd8-bcbd-5b04e3218fc3">
</p>
<p align="center">
Fig 5.
</p>

## Output
<p align="center">
<img width="491" alt="image" src="https://github.com/Veda1809/Layout_Design/assets/142098395/426198ee-d91b-4af7-9197-b2882230aaa8">
</p>
<p align="center">
Fig 6.
</p>

## Layout of Mirror Circuit
<p align="center">
<img width="509" alt="image" src="https://github.com/Veda1809/Layout_Design/assets/142098395/acf352da-8bd1-474f-af79-dcd91b159fe6">
</p>
<p align="center">
Fig 7.
</p>

## Conclusion
The mirror circuit and conventional circuit of Full Adder uses total of **28 transistors**.

