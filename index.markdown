---
layout: default
title: Home
permalink: /
---
# Mohammed Pivezhandi

Welcome to my academic website! I am a PhD candidate in the Department of Computer Science at Wayne State University, working in the Embedded Systems Lab under the supervision of Dr. Abusayeed Saifullah. My research focuses on **data-efficient AI-guided energy- and thermal-aware scheduling on heterogeneous multicore systems**, aiming to optimize energy consumption, thermal management, and performance in embedded systems. With a background in high-performance computing, reinforcement learning, and computer architecture, I have extensive experience in both software and hardware design for real-time systems.

---

## About Me

I hold a Master's degree in Computer Science/Engineering from Iowa State University (CGPA: 3.76/4.0) and a Master's in Digital Electronics from Shahid Beheshti University (CGPA: 4.0/4.0), where my thesis focused on statistical analysis and implementation of neural networks for human activity recognition. I also earned a Bachelor's in Electronic Engineering from Ferdowsi University of Mashhad. My career spans research and teaching roles at Wayne State University, Iowa State University, and Shahid Beheshti University, alongside industry experience as a research intern at Moffett Systems, Inc., where I worked on FPGA prototyping and hardware accelerator design.

My technical skills include programming in Python, C/C++, MATLAB, and Java; hardware description using VHDL and Verilog; and application development with TensorFlow, PyTorch, CUDA, OpenMP, and MPI. I am fluent in English and Persian, and my hobbies include playing the piano, chess, cooking, and running.

---

## Research Overview

My dissertation, titled *Data-Efficient AI-Guided Energy- and Thermal-Aware Scheduling on Heterogeneous Multicore Systems*, addresses the critical challenge of energy and thermal management in embedded multicore platforms. As power density doubles every three years, energy consumption, heat production, and cooling costs (nearly 3 dollars per watt of heat dissipation) pose significant concerns, while overheating degrades system reliability.

### Research Goals

- **Performance-efficient scheduling**: Minimize energy consumption and makespan (execution time) for parallel DAG workloads.
- **Thermal-aware management**: Reduce temperature hotspots to enhance system reliability.

### Approach

I leverage **Hierarchical Multi-Agent Reinforcement Learning (HMARL)** and **data-efficient RL techniques** to achieve scalable, energy- and thermal-aware scheduling. Key components include:

- **HMARL**: Reduces the action space complexity from O(m^n) to O(m * n) using Profiler, Thermal, and Priority agents.
- **Data-efficient learning**: Employs few-shot RL with distribution-aware flow matching and synthetic data generation to improve sample efficiency.
- **Feature-aware task allocation**: Balances energy, makespan, and temperature using statistical learning methods (e.g., Random Forest, Pearson correlation).
- **Scalable framework**: Adapts to heterogeneous platforms like Jetson TX2 and Intel Core i7, supporting applications such as neuromorphic vision workloads.

### PhD Contributions

- **HMARL for OpenMP DAG Workloads**: Achieved 31.7% energy reduction and 34.1% makespan improvement (Published RTSS 2024 WIP, Submitted to EMSOFT 2025).
- **Feature-Aware Task Allocation**: Reduced energy by 10% and temperature by 5 degrees Celsius (Submitted to RTCSA 2025).
- **Distribution-Aware Flow Matching for Few-Shot RL**: Improved frame rates by 30% in few-shot settings (Submitted to ECAI 2025).

### Future Research (Due January 1 2026)

- **Model-Based MARL for DVFS (Real-Time)**: Extend MARL to handle continuous action spaces using DDPG/PPO, with LLM-based environment modeling for real-time task prioritization.
- **LLM-Driven CFG-Based Code Optimizer (AI)**: Use LLMs to generate control-flow graphs (CFGs) from OpenMP code, enabling RL-based resource allocation and code variation selection (e.g., tied, untied, serial) to minimize makespan.

---
