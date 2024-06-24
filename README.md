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

## Week 2 - uarch

- [Yorktown simulation engine](https://ieeexplore.ieee.org/document/1585479)
- [Logic simulation engines in Japan](https://ieeexplore.ieee.org/abstract/document/43078?casa_token=nD2xnLdyzTYAAAAA:rY_2eFFqS8Imhzso9TwMOKM2qQ6E5eQ0rZVc54LK_iRS4cVwM2CNewPATFflru2O-nGR-r7kvNg)

## Week 3 - compiler

- [Yorktown simulation SW support](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1585481)

## Week 4 - compiler

- [Load and Communications Balancing on Multiprocessor Logic Simulation Engines](https://web.archive.org/web/20170222020308id_/http://openscholarship.wustl.edu/cgi/viewcontent.cgi?article=1814&context=cse_research)

## Week 5 - compiler

- [Efficient circuit partitioning algorithms for parallel logic simulation](https://dl.acm.org/doi/abs/10.1145/76263.76303)
- [Multiple-level partitioning: an application to the very large-scale hardware simulator](https://ieeexplore.ieee.org/abstract/document/78241?casa_token=DJP4vvOHJxMAAAAA:GWONYTISKBjXjdnueyLsLCknZq9MFjiwGPbg-UCdpj6g05_DYEf6nEZebsIC7V-cXWlgTMNbILY)


## Week 6 - misc

- [performance analysis of parallel logic simulation machine](https://www.sciencedirect.com/science/article/pii/0743731589900294?)
- [Emulating multi-ported memory circuits](https://patents.google.com/patent/US5940603A/en)

## Week 7 - Power & gate level simulation

- CPF_palladium (cadence manual)
- LowPowerCPF-Simulation-Guide (cadence manual)

## Week 8 - FPGA based emulation

- [Time multiplexed FPGA architecture for logic emulation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=518231)
- [CAD fromwork for Malibu: an FPGA with time-multiplexed coarse-grained elements](https://dl.acm.org/doi/abs/10.1145/1950413.1950441)
