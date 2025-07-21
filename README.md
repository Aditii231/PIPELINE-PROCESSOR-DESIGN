# PIPELINE-PROCESSOR-DESIGN

COMPANY: CODTECH IT SOLUTIONS

NAME: ADITI ATTAL

INTERN ID: CITS0D695

DOMAIN: VLSI

DURATION: 6 WEEKS

MENTOR: NEELA SANTOSH

DISCRIPTION:
1.Instruction and Pipeline Modeling:
The code represents instructions (ADD, SUB, LOAD) as MATLAB structs and models each stage of the pipeline (IF, ID, EX, WB) using separate pipeline registers to simulate instruction flow over clock cycles.

2.Register File and Memory Setup:
A simple register file (registers) and data memory (data_memory) are implemented as arrays. Initial values are assigned to simulate meaningful arithmetic and memory access operations.

3.Cycle-Based Simulation:
The processor is simulated over multiple clock cycles, and at each cycle, instructions move through the pipeline stages. The PC (program counter) controls fetching from the instruction memory.

4.Stage-Wise Execution and Data Handling:
IF fetches instructions from memory
ID decodes and reads register operands
EX performs ALU operations or calculates memory address
WB writes results back to the register file

5.Pipeline Visualization and Result Display:
Each clock cycle’s pipeline state is printed in a table format showing which instruction is in each stage. At the end, the final state of all registers is displayed to verify correctness of the simulation.

OUTPUT:

<img width="1221" height="569" alt="Image" src="https://github.com/user-attachments/assets/73942e9d-eac9-44c1-a162-9a8836157bc3" />
