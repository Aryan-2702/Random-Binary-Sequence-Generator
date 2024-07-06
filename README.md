# Random-Binary-Sequence-Generator

A PRBS generator produces a pseudo-random binary sequence, which mimics a random sequence of binary numbers. These sequences are crucial for testing high-speed communication systems by serving as test signals. PRBSs are employed to thoroughly assess dynamic performance and are particularly useful for conducting bit error rate (BER) testing, ensuring comprehensive verification of system functionality under various conditions.

With the increasing demand for high-speed circuits to achieve higher data rates, there is a corresponding need for advanced PRBS generators. Individual building blocks such as latches, D flip-flops (DFFs), and XOR gates draw high current to implement it. These components require large devices to handle the currents, resulting in increased area requirements. 

The Conventional Random Bits Generator core requires high power consumption for this operation. Parallel implementations of the PRBS and Linear Feedback Shift Register are examples of the traditional  generator. Above is the verilog implementation of the same.

The Proposed PRBS introduces an architecture that efficiently generates four uncorrelated maximum length random sequences using fewer building blocks. It aims to reduce required building blocks compared to conventional one. This advancement is verified using verilog synthesis and hardware realization on the FPGA Board.

# The specific code and circuit diagram of the proposed PRBS cannot be shared due to copyright constraints. However, the resulting output waveform from this PRBS design is available for review and analysis.



