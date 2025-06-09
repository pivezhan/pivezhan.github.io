---
layout: default
title: Projects
permalink: /projects
---

# Projects

My research focuses on AI-guided scheduling, reinforcement learning, high-performance computing, and hardware design for energy-efficient systems. Below is a summary of my key projects, spanning real-time systems, resource scheduling, machine learning, and FPGA/ASIC design.

## Energy- and Thermal-Aware Scheduling for OpenMP DAG Workloads (2022–2025)
**Wayne State University, Detroit, MI**  
Developed a Hierarchical Multi-Agent Reinforcement Learning (HMARL) framework for energy- and performance-aware scheduling of OpenMP DAG workloads on heterogeneous multicore platforms (e.g., Jetson TX2, Intel Core i7).  
- Achieved 31.7% energy reduction and 34.1% makespan improvement.  
- WIP Published at *RTSS 2024* and Submitted to *RTSS 2025*.  
- Technologies: Python, TensorFlow, OpenMP, Linux.

## Feature-Aware Task-to-Core Allocation in Heterogeneous Platforms (2023–2025)
**Wayne State University, Detroit, MI**  
Designed a statistical learning framework using Random Forest, backward stepwise regression, and Pearson correlation for task-to-core allocation on multicore processors.  
- Reduced energy consumption by 10% and core temperature by 5°C.  
- Published at *RTCSA 2025*.
- Technologies: Python, MATLAB, R, Linux.

## Distribution-Aware Flow-Matching for Few-Shot Reinforcement Learning (2023–2025)
**Wayne State University, Detroit, MI**  
Developed a distribution-aware flow-matching approach to enhance few-shot reinforcement learning in Dynamic Voltage and Frequency Scaling (DVFS) settings.  
- Improved frame rates by 30% in few-shot scenarios.  
- Submitted to *ECAI 2025*.  
- Technologies: PyTorch, Python, CUDA, Linux.

## Model-Based Multi-Agent Reinforcement Learning for DVFS Optimization (2024–Ongoing)
**Wayne State University, Detroit, MI**  
Working on a model-based MARL framework incorporating LLM-based environment modeling for real-time task prioritization and DVFS optimization.  
- Planned submission to *RTAS 2025*.  
- Technologies: Python, TensorFlow, LLMs, C++, Linux.

## LLM-Driven CFG-Based Code Optimizer for OpenMP (2025–Ongoing)
**Wayne State University, Detroit, MI**  
Developing an LLM-driven framework to generate control-flow graphs (CFGs) from OpenMP code, using hierarchical MARL and compressed learning (PEFT, RAG) to select optimal code variations (e.g., tied, untied, serial) for minimizing makespan.  
- Planned submission to *AAAI 2025*.  
- Technologies: Python, PyTorch, LLMs, OpenMP.

## Energy-Aware Real-Time Scheduling for Xeon Processors (2021–2022)
**Iowa State University, Ames, IA**  
Designed energy-aware scheduling algorithms for DAG-based inputs targeting Intel Xeon processors in data-processing clusters.  
- Developed a simulator for dynamic resource allocation based on task DAGs.  
- Technologies: C, Python, OpenMP, MPI.

## Learning-Based Scheduler for Data Warehouse using Graph Neural Networks (2020–2021)
**Iowa State University, Ames, IA**  
Developed a reinforcement learning-based scheduler using Graph Neural Networks (GNNs) for high-volume ETL processing in data warehouse systems.  
- Combined task graphs into a single graph for efficient state representation, with message passing from leaf to root nodes to enhance embedding features.  
- Achieved up to 15% improvement in job completion time compared to state-of-the-art ML schedulers and 20% compared to tuned heuristic schedulers.  
- Published at *[PDCAT 2021](https://link.springer.com/chapter/10.1007/978-3-030-96772-7_17)*.  
- Technologies: Python, TensorFlow.

## FPGA-Based Histogram for Event-Based Optical Flow Calculation (2020–2021)
**Iowa State University, Ames, IA**  
Designed an FPGA-based architecture for histogram generation to support event-based camera optical flow calculation, optimizing memory and logic resources.  
- Stored time differences between consecutive events, reducing time encoding from 32 to 7 bits with ~3% loss in histogram accuracy across three benchmarks.  
- Achieved significant speedup compared to software implementation.  
- Published at *[ASAP 2020](https://ieeexplore.ieee.org/abstract/document/9153247)*. 
- Technologies: VHDL, FPGA, Java, Python.

## FPGA Prototyping for Hardware Acceleration (2020–2021)
**Moffett Systems, Inc., Los Altos, CA**  
Contributed to full-stack hardware accelerator design, including FPGA prototyping, RTL design, compiler development, firmware, and runtime.  
- Focused on implementation, verification, debugging, and bring-up.  
- Technologies: VHDL, Verilog HDL, Vivado HLS, FPGA.

## High-Throughput Matrix Inversions for MIMO on FPGA (2015–2018)
**Mashhad Researchers Center, Mashhad, Iran**  
Designed and implemented high-throughput matrix inversions for MIMO wireless applications using the Gauss-Jordan algorithm on FPGA.  
- Optimized for performance using RTL design.  
- Technologies: VHDL, ISE Design Suite, FPGA.

## Fault-Tolerant Systems on FPGA (2015–2018)
**Mashhad Researchers Center, Mashhad, Iran**  
Conducted reliability analysis and implemented fault-tolerant systems on FPGA using HDL and SystemC, with evaluations via MATLAB simulations.  
- Focused on information and modular redundancy.  
- Technologies: VHDL, SystemC, MATLAB, FPGA.


## Statistical-Based Neural Network for Human Activity Recognition (2013–2015)
**Shahid Beheshti University, Tehran, Iran**  
Designed and implemented a hybrid model combining statistical feature compression and neural network architecture for human activity recognition tasks.  
- Achieved over 99% mean accuracy using P-value-based dimensional reduction in feature space.  
- Proposed a model suitable for hardware implementation in gesture recognition applications.  
- Published at *[Int. J. Comput. Appl.](https://www.researchgate.net/profile/Babak-Maybodi/publication/283161910_Statistical_based_Neural_Network_in_Human_Activity_Recognition/links/5b6e979b45851546c9faa4d7/Statistical-based-Neural-Network-in-Human-Activity-Recognition.pdf)*.  
- Technologies: R, VHDL, FPGA.

## Statistical-Based Models for CNT-FET Applications (2014–2015)
**Shahid Beheshti University, Tehran, Iran**  
Developed statistical-based models for carbon nanotube field-effect transistors (CNT-FETs) using support vector regression and random forest algorithms to improve simulation accuracy and speed.  
- Achieved 9% error for off-state current with random forest, eightfold more accurate than previous ANN-based models, with over ten times faster learning time.  
- Published at *[Springer J. Comput. Electron.](https://www.researchgate.net/publication/319146972_Accuracy_improvement_with_reliable_statistical-based_models_for_CNT-FET_applications)*.  
- Technologies: R, MATLAB.

## ASIP Design for CORDIC-Based DFT and DCT Algorithms (2013–2014)
**Shahid Beheshti University, Tehran, Iran**  
Designed an Application-Specific Instruction-set Processor (ASIP) using CORDIC methods for two-dimensional Discrete Fourier Transform (DFT) and Discrete Cosine Transform (DCT) algorithms, optimized for signal processing and image compression.  
- Reduced gate count in the control unit by 84% for DFT and 86% for DCT compared to the Mano design, with 3.6% and 3.86% clock cycles, respectively.  
- Published at *[ICCKE 2016](https://ieeexplore.ieee.org/document/7802151/)*.  
- Technologies: VHDL, RTL.

## AES Cryptography Implementation on Spartan-6 FPGA (2013–2014)
**Mashhad Researchers Center, Mashhad, Iran**  
Implemented the AES cryptography algorithm on Spartan-6 FPGA with optimized RTL design.  
- Simulated and verified using ActiveHDL and ISE Design Suite.  
- Technologies: MATLAB, VHDL, ISE Design Suite, FPGA.

## Low-Power ASIC Layout for 8-Bit Multiplier (2013–2015)
**Shahid Beheshti University, Tehran, Iran**  
Designed a low-power, high-frequency ASIC layout for an 8-bit multiplier using pseudo-nMOS and pseudo-pMOS gates.  
- Technologies: Virtuoso, OrCAD, Spice.

