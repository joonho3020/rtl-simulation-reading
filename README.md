# RTL Simulation Reading Group Notes

## Papers / Patents

### Emulation HW

- [Multiprocessor for HW emulation](https://patents.google.com/patent/US5551013A/en)
- [Emulating multi-ported memory circuits](https://patents.google.com/patent/US5940603A/en)
- [Yorktown simulation engine](https://ieeexplore.ieee.org/document/1585479)
- [A survey of HW accelerators used in CAD](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5005647)
- [VLSI Logic and Fault Simulation on GP Parallel Computers](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=215006)
- [Logic simulation engines in Japan](https://ieeexplore.ieee.org/abstract/document/43078?casa_token=nD2xnLdyzTYAAAAA:rY_2eFFqS8Imhzso9TwMOKM2qQ6E5eQ0rZVc54LK_iRS4cVwM2CNewPATFflru2O-nGR-r7kvNg)
- [Sahara: Massively parallel dedicated hardware for cycle-based logic simulations, Hanamura et. al., 2005](https://onlinelibrary.wiley.com/doi/epdf/10.1002/ecjc.20193)
- [Speeding Up Look-up-Table Driven Logic Simulation., Murgai et. al., 1999](./resources/emulation/Speeding up lookup table driven logic simulation.pdf)

### Time multiplexed FPGA

- [Time multiplexed FPGA architecture for logic emulation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=518231)
- [A CAD framework for Malibu: an FPGA with time-multiplexed coarse-grained elements](https://dl.acm.org/doi/abs/10.1145/1950413.1950441)

### Academic attempts

- [Accelerating RTL Simulation with Hardware-Software Co-Design (MICRO 23)](https://dl.acm.org/doi/abs/10.1145/3613424.3614257)
- [Cyclist](https://dl.acm.org/doi/abs/10.1109/ICCAD.2017.8203892)
  - https://github.com/palmer-dabbelt/flo-llvm
  - https://github.com/palmer-dabbelt/libflo
  - Chisel DREAMER emulation platform: https://wiki.eecs.berkeley.edu/dreamer/Main/20141203Notes
- [Manticore: Hardware-Accelerated RTL Simulation with Static Bulk-Synchronous Parallelism (ASPLOS 23)](https://dl.acm.org/doi/10.1145/3623278.3624750)

### Compiler partitioning strategy

- [Yorktown simulation SW support](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1585481)
- [Load and Communications Balancing on Multiprocessor Logic Simulation Engines](https://web.archive.org/web/20170222020308id_/http://openscholarship.wustl.edu/cgi/viewcontent.cgi?article=1814&context=cse_research)
- [Efficient circuit partitioning algorithms for parallel logic simulation](https://dl.acm.org/doi/abs/10.1145/76263.76303)
- [Multiple-level partitioning: an application to the very large-scale hardware simulator](https://ieeexplore.ieee.org/abstract/document/78241?casa_token=DJP4vvOHJxMAAAAA:GWONYTISKBjXjdnueyLsLCknZq9MFjiwGPbg-UCdpj6g05_DYEf6nEZebsIC7V-cXWlgTMNbILY)
- [performance analysis of parallel logic simulation machine](https://www.sciencedirect.com/science/article/pii/0743731589900294?)

### FireSim ancestors

- [FPGA-Accelerated Simulation Technologies (FAST): Fast, Full-System, Cycle-Accurate Simulators (MICRO 2007)](https://ieeexplore.ieee.org/abstract/document/4408260)
- [RAMP: Research Accelerator for Multiple Processors (IEEE Micro 2007)](https://ieeexplore.ieee.org/abstract/document/4287395)
- [RAMP Blue: A Message-Passing Manycore System in FPGAs (FPL 2007)](https://ieeexplore.ieee.org/abstract/document/4380625)
- [RAMP Blue: Implementation of a Manycore 1008 Processor FPGA System (RSSI 2008)](http://people.eecs.berkeley.edu/~krste/papers/Burke_RAMP_Blue_RSSI_2008.pdf)
- [A-Ports: an efficient abstraction for cycle-accurate performance models on FPGAs (FPGA 2008)](https://dl.acm.org/doi/pdf/10.1145/1344671.1344685)
- [Quick Performance Models Quickly: Closely-Coupled Partitioned Simulation on FPGAs (ISPASS 2008)](https://ieeexplore.ieee.org/abstract/document/4510733)
- [A-Port Networks: Preserving the Timed Behavior of Synchronous Systems for Modeling on FPGAs (2009)](https://dl.acm.org/doi/abs/10.1145/1575774.1575775)
- [ProtoFlex: Towards Scalable, Full-System Multiprocessor Simulations Using FPGAs (2009)](https://dl.acm.org/doi/abs/10.1145/1534916.1534925)
- [The Future of Architectural Simulation (IEEE Micro 2010)](https://ieeexplore.ieee.org/abstract/document/5506934)
- [RAMP gold: an FPGA-based architecture simulator for multiprocessors (DAC 2010)](https://dl.acm.org/doi/abs/10.1145/1837274.1837390)
- [A case for FAME: FPGA architecture model execution (ISCA 2010)](https://dl.acm.org/doi/abs/10.1145/1815961.1815999)
- [HAsim: FPGA-based high-detail multicore simulation using time-division multiplexing (HPCA 2011)](https://ieeexplore.ieee.org/abstract/document/5749747)
- [Leveraging latency-insensitivity to ease multiple FPGA design (FPGA 2012)](https://dl.acm.org/doi/abs/10.1145/2145694.2145725)
- [A cycle-accurate, cycle-reproducible multi-FPGA system for accelerating multi-core processor simulation (FPGA 2012)](https://dl.acm.org/doi/abs/10.1145/2145694.2145720)
- [Golden Gate: Bridging The Resource-Efficiency Gap Between ASICs and FPGA Prototypes (ICCAD 2019)](https://ieeexplore.ieee.org/abstract/document/8942087)
- [FASED: FPGA-Accelerated Simulation and Evaluation of DRAM (FPGA 2019)](https://dl.acm.org/doi/abs/10.1145/3289602.3293894)

### HDL history

- [Hardware design and description languages in IBM](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5390297)
- [A Golden Age of Hardware Description Languages: Applying Programming Language Techniques to Improve Design Productivity (SNAPL 2019)](https://drops.dagstuhl.de/storage/00lipics/lipics-vol136-snapl2019/LIPIcs.SNAPL.2019.7/LIPIcs.SNAPL.2019.7.pdf)

### Power, gate level simultion

- CPF_palladium
- LowPowerCPF-Simulation-Guide

### Software RTL Simulation

- [LiveSim: A Fast Hot Reload Simulator for HDLs (ISPASS 2020)](https://ieeexplore.ieee.org/abstract/document/9238634)
- [A Case for Accelerating Software RTL Simulation by Scott Beamer (IEEE Micro 20)](https://ieeexplore.ieee.org/abstract/document/9099598)
- [ESSENT: Efficiently Exploiting Low Activity Factors to Accelerate RTL Simulation (DAC 20)](https://ieeexplore.ieee.org/abstract/document/9218632)
- [Fast behavioural rtl simulation of 10b transistor soc designs with metro-mpi (DATE 23)](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10137080)
- [RepCut: Superlinear Parallel RTL Simulation with Replication-Aided Partitioning (ASPLOS 23)](https://dl.acm.org/doi/abs/10.1145/3582016.3582034)
- [On Accelerating PyRTL Simulation with Essential Signal Simulation Techniques (ISEDA 23)](https://ieeexplore.ieee.org/abstract/document/10218453)
- [Khronos: Fusing Memory Access for Improved Hardware RTL Simulation (MICRO 23)](https://dl.acm.org/doi/abs/10.1145/3613424.3614301)
- [TaroRTL: Accelerating RTL Simulation using Coroutine-based Heterogeneous Task Graph Scheduling (Euro-Par 24)](https://jsm.ece.wisc.edu/docs/lin-europar2024.pdf)

### HW-Accelerated (Non-FPGA) RTL Simulation

- [RTLFlow: From RTL to CUDA: A GPU Acceleration Flow for RTL Simulation with Batch Stimulus (ICPP 22)](https://dl.acm.org/doi/abs/10.1145/3545008.3545091)
- [Parendi: Thousand-Way Parallel RTL Simulation (Arxiv Preprint 24)](https://arxiv.org/abs/2403.04714)

---

## Tentative schedule

## Week 1 - uarch

- [Multiprocessor for HW emulation](https://patents.google.com/patent/US5551013A/en)

### Summary

#### Processor design

- Instructions execute step by step (no control flow, fixed set of instructions in IMEM). Each iteration through the instruction memory corresponds to one target cycle
- Two data memory (denoted as input/data stack)
    - In each step, the function bit out (FBO) is stored in the data stack
    - In each step, the input from the switch is stored in the input stack. Instruction encodes which other processor to accept the incoming switch bit from (a bit can be ignored or broadcasted to X other processors)
    - Need to perform logic computation in a BFS manner in order to use the values created from previous steps
- LUTs are configured to simulate arbitrary N-1 gates. Operands are read from the input/data stack.
- Bits can be forwarded to nearby processor (N-3 ~ N+3) instead of going through the network.
    - Way of saving one cycle: if the bit goes over the network, to use it, the processor has to store it in the input stack and use it in the following cycle
- Instruction memory is split into two parts: left and right
    - For logic emulation, left and right both encodes the operation to perform
    - For memory (SRAM?) emulation, the right instruction is essentially the data array. 16 processors are grouped and a bit from each group is used to generate the address for the memory operation

#### Emulation module, board, platform

- Module
    - 64 processors are grouped together as a module
    - All the processors within a module are connected as a crossbar
- Board
    - Collection of emulation modules
    - Module ports are connected in a pre-configured fashion
- Platform
    - Collection of boards, DRAM(?), host communication logic, and other platform control logic
- Need to synchronize across every cycle across all boards. How should this global synchronization achieved? Also can we allow certain parts to slip ahead of this global synchronization barrier (I think we can, but the  benefit might not be significant due to straggler effects)

---

- Can connect multiple processors to simulate logic where the logic depth is larger than the max steps
    - The performance degradation as the target design size increases is gradual
- Inter board communication has to happen in fixed latency / compiler is aware of the latency (to the compiler, the link doesn't really matter except that the scheduling might change a little bit)
- Need to have a core that can run testbench code near the machine (display messages, assertions, C++ models ...)
- For 4 state, just use software and inject state
    - However, there are other cases where 4 state sim make sense : external IP can inject 4 state, low power simulation...
    - Cadence added support for X-prop in their latest Palladium
    - Problem with X-prop is that you have to use 2 bits to simulate a single bit (00 -> 0, 01 -> 1, 10 -> X, 11 -> Z) but can be very area inefficient (especially X's are a rare state compared to just 0 & 1)
    - But for the problems that we are trying to deal with (functional & performance verification) 2 state simulation may be sufficient
- Expanding SRAM depth is cheap because we can use custom macros
    - So when you can increase the frequency of the design, you would want to increase the SRAM depth so that each processor can emulate more gates w/o performance loss
    - However, if the frequency is fixed, increasing the number of steps per cycle translates to lower simulation perf
    - So that seems to be the reason that the IBM people found out 128 steps
    - Need to find the optimal step for FPGA & ASIC w/ modern technology nodes.
- One implementation option: add the processor grid as a FireSim LI-BDN where the interface is fixed (e.g., your tile)
    - Can share the FireSim bridge/IO infrastructure
    - Can save FPGA resources by mapping parts of the design directly on the FPGA and only the part where you anticipate RTL changes on the emulation processors
    - For Fpga overlay (300 MHz), may have to make the network more simple to save FPGA routing resources
        - The compiler has to be aware of the network latency (network has to be designed to have static latency & maps well onto an FPGA in such a way it matches switch boxes well)
        - The compiler has to be able to pipeline instructions to hide extra network latency
    - GCD is a good place to start
    - FMR will increase (perhaps similar to when running TracerV)
        - Jerry's opinion is that we shouldn't try to compromise on performance
        - In my opinion, this is somewhat inevitable and not too bad
- Approximating how many gates we can emulate when using a FPGA overlay
    - FPGA can simulate N ASIC gates
    - Each emulation processor corresponds to M ASIC gates, and has max T steps (T gates)
        - M has to take account of the network
    - Gates that can be emulated is approximately (N / M * T)
    - Need to measure T/M by implementing a dummy module and building a bitstream with it

### Discussion/Questions

- Should the compiler always cut across register boundaries?
    - If a RTL block mapped to a single processor contains sequential logic, the processor cannot use the bit in the data stack that correpsonds to the FF as it will be overwritten. So that bit must go across the network and come back and the compiler would have to insert NOPs. -> utilization vs performance tradeoff
    - Alternatively, can double the on-chip memory so that each half can work like a master (producing bits) and slave (storing bits for the next cycle). This enables more partitioning flexibility in the compiler but decreases area efficiency of the processors
- How many processors can fit in a single FPGA & how many processors/modules/boards would we need to simulate a reasonably sized CY SoC?
- What are some problems that might show up when scaling this system up in such a way that it can support a billion gate simulation?
- (Since this word seems like some magic keyword to people) Heterogeneous integration of processor designs? Can we design certain modules/blocks to have different number of operands, bitwidth, ... to optimize for area & performance?
- How to do X-propagation? We can encode that by just using 2 bits instead of 1 bit but that will have a significant area overhead. However, the most recent palladium started supporting X-propagation as well. Maybe they only have certain processors that have X-modeling while most processors only support 2 state simulation? Static analysis to identify gates that will not be X's for certain.


## Week 2 - uarch

- [Yorktown simulation engine](https://ieeexplore.ieee.org/document/1585479)
- [Logic simulation engines in Japan](https://ieeexplore.ieee.org/abstract/document/43078?casa_token=nD2xnLdyzTYAAAAA:rY_2eFFqS8Imhzso9TwMOKM2qQ6E5eQ0rZVc54LK_iRS4cVwM2CNewPATFflru2O-nGR-r7kvNg)

## Week 3 - compiler

- [Yorktown simulation SW support](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1585481)

## Week 4 - compiler

- [Multiple-level partitioning: an application to the very large-scale hardware simulator](https://ieeexplore.ieee.org/abstract/document/78241?casa_token=DJP4vvOHJxMAAAAA:GWONYTISKBjXjdnueyLsLCknZq9MFjiwGPbg-UCdpj6g05_DYEf6nEZebsIC7V-cXWlgTMNbILY)

## Week 5 - compiler

- ~~~[Load and Communications Balancing on Multiprocessor Logic Simulation Engines](https://web.archive.org/web/20170222020308id_/http://openscholarship.wustl.edu/cgi/viewcontent.cgi?article=1814&context=cse_research)~~~
- [Efficient circuit partitioning algorithms for parallel logic simulation](https://dl.acm.org/doi/abs/10.1145/76263.76303)

## Week 6 - misc

- [performance analysis of parallel logic simulation machine](https://www.sciencedirect.com/science/article/pii/0743731589900294?)
- [Emulating multi-ported memory circuits](https://patents.google.com/patent/US5940603A/en)

## Week 7 - Power & gate level simulation

- CPF_palladium (cadence manual)
- LowPowerCPF-Simulation-Guide (cadence manual)

## Week 8 - FPGA based emulation

- [Time multiplexed FPGA architecture for logic emulation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=518231)
- [CAD fromwork for Malibu: an FPGA with time-multiplexed coarse-grained elements](https://dl.acm.org/doi/abs/10.1145/1950413.1950441)
