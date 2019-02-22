1. 
Shengqi Wang, sw979
2. 
In my ALU, there are four parst:
For the first part, AND, OR, XOR and NOR, gate delay is 3;
For the second part, for EQ, NE, LE and GT, gate delay is 6;
For the third part, for ADD and SUBSTRACT, gate delay is 100;
For the forth part, for shifting, gate delay is 8;
As a result, ADD or SUBSTRACT operation is critical path. 
3.
There are four parts in ALU:
(1) Add32 contains 161 gates;
(2) Shift contains 680 gates;
(3) GateALU contains 289 gates;
(4) CompareALU contains 216 gates;
Totally there are 1346 gates, and add gates in ALU (194 gates):
1346+194=1540 gates;