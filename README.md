# Router_1x3_Design
Designed and implemented a 1x3 packet router capable of directing data packets from a single source network to three independent client destinations. The architecture included a register module for temporary data storage, three FIFO memory blocks for queuing packets per client, a Finite State Machine (FSM) for routing logic, and a synchronizer for internal signal coordination. The majority of the design was simulated and verified using Xilinx ISE and ISIM. Code coverage analysis was performed using QuestaSim, followed by testbench-based verification in a UVM (Universal Verification Methodology) environment to ensure RTL compliance and functional correctness.


Architectural design of data router in Verilog
![image](https://github.com/user-attachments/assets/d4c7a245-e8d3-4693-af34-62728ea781fd)
