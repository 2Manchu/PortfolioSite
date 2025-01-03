---
title: "Computational Storage for Data Integrity and Security (MSST '24)" # Title of your project
date: 2024-02-06T10:15:15-06:00
weight: 1 # Order in which to show this project on the home page
external_link: "" # Optional external link instead of modal
resources:
    - src: msst_abstract.png
      params:
          weight: 0 # Optional weighting for a specific image in this project folder
draft: false
project_timeframe: "January 2024 - May 2024"
---

Research project undertaken by myself and a Computer Engineering Ph.D student for an advanced data storage systems class. The goal of this project is to research and analyze the viability of using computational storage devices for accelerating tasks common to data integrity and ransomware protection schemes. We have identified research gaps in erasure coding and data security tasks and their applicability to computational storage devices and developed a proof-of-concept library (CSDGuard) using C++ and OpenCL that implemented I/O operations, computations, and performance measurement utilities common to those tasks. We then synthesized and optimized a hardware-based accelerator kernel using AMD Vitis High-Level Synthesis tools, and were able to observe up to a 70% performance increase utilizing CSDGuard over a reference software-based implementation. Our work was accepted to be a part of the poster presentation portion of the 2024 Massive Storage Systems and Technology conference in Santa Clara, CA.