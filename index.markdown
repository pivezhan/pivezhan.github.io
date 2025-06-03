---
---
layout: default
title: Home
---

# Mohammed Pivezhani's Academic Site

Welcome to my academic website! I am a PhD candidate in the Department of Computer Science at Wayne State University, working in the Embedded Systems Lab under the supervision of Dr. Abusayeed Saifullah. My research focuses on **data-efficient AI-guided energy- and thermal-aware scheduling on heterogeneous multicore systems**, aiming to optimize energy consumption, thermal management, and performance in embedded systems.

---

## Research Overview

My dissertation, titled *"Data-Efficient AI-Guided Energy- and Thermal-Aware Scheduling on Heterogeneous Multicore Systems"*, addresses the critical challenge of energy and thermal management in embedded multicore platforms. As power density doubles every three years, energy consumption, heat production, and cooling costs (nearly $3 per watt of heat dissipation) pose significant concerns, while overheating degrades system reliability.

### Research Goals
- **Performance-efficient scheduling**: Minimize energy consumption and makespan (execution time) for parallel DAG workloads.
- **Thermal-aware management**: Reduce temperature hotspots to enhance system reliability.

### Approach
I leverage **Hierarchical Multi-Agent Reinforcement Learning (HMARL)** and **data-efficient RL techniques** to achieve scalable, energy- and thermal-aware scheduling. Key components include:
- **HMARL**: Reduces the action space complexity from \(O(m^n)\) to \(O(m \times n)\) using Profiler, Thermal, and Priority agents.
- **Data-efficient learning**: Employs few-shot RL with distribution-aware flow matching and synthetic data generation to improve sample efficiency.
- **Feature-aware task allocation**: Balances energy, makespan, and temperature using statistical learning methods (e.g., Random Forest, Pearson correlation).
- **Scalable framework**: Adapts to heterogeneous platforms like Jetson TX2 and Intel Core i7, supporting applications such as neuromorphic vision workloads.

### Completed Contributions
- **HMARL for OpenMP DAG Workloads**: Achieved 31.7% energy reduction and 34.1% makespan improvement (Published RTSS ’24 WIP, Submitted to EMSOFT’25).
- **Feature-Aware Task Allocation**: Reduced energy by 10% and temperature by 5°C (Submitted to RTCSA ’25).
- **Distribution-Aware Flow Matching for Few-Shot RL**: Improved frame rates by 30% in few-shot settings (Submitted to ECAI ’25).

### Proposed Research (Next 6–7 Months)
- **Model-Based MARL for DVFS (Real-Time)**: Extend MARL to handle continuous action spaces using DDPG/PPO, with LLM-based environment modeling for real-time task prioritization.
- **LLM-Driven CFG-Based Code Optimizer (AI)**: Use LLMs to generate control-flow graphs (CFGs) from OpenMP code, enabling RL-based resource allocation and code variation selection (e.g., tied, untied, serial) to minimize makespan.

### Timeline
- **Months 1–2 (June–July 2025)**: Develop Model-Based MARL and train LLM for CFG generation.
- **Months 3–4 (August–September 2025)**: Evaluate frameworks and integrate hybrid verification.
- **Months 5–6 (October–November 2025)**: Prepare manuscripts for RTAS and AAAI-25.

---

## About This Site

This website is hosted on [GitHub Pages](https://pages.github.com/), a free service that builds and hosts websites from code stored in a GitHub repository. Each time I update my repository, the site automatically rebuilds to reflect the latest content.

Explore the tabs above to learn more about my [publications](#), [news](#), [teaching](#), [CV](#), and [projects](#).

---
