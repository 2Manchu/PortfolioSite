---
title: "CPRE 381: VHDL Processor Design" # Title of your project
date: 2023-01-21T10:33:47-06:00
weight: 1 # Order in which to show this project on the home page
external_link: "" # Optional external link instead of modal
resources:
  - src: "mips-risc.jpg"
    params:
      weight: 0
project_timeframe: "January 2023 - May 2023"
draft: false
---

CPRE 381: Computer Organization and Assembly Level Programming. This project as a whole spanned several months, from February until the end of the semester, with the overall goal of designing several processors around the MIPS ISA with the final goal of comparing their performance. It relied heavily on applying concepts from class, including VHDL skills, piplining, hazard avoidance, and general knowledge of digital logic and the MIPS ISA. This project was completed in a team of two, with both members utilizing Git for version control. Due my partner's high workload that semester, I was primarily responsbile for the top-level design and integration of the processor, as well as unit testing as features were added. All designs included in the below repository implement the core MIPS ISA, and will run an arbitrary MIPS assembly program (examples included). This project greatly enhanced my understanding of the process of debugging and fixing design issues, which I was introduced to in my first co-op at Western Digital the months prior. This project also familiarized me with the concept of design synthesis, and how different design strategies impact the critical path, and therefore the maximum theoretical clock speed of the processor.

The GitHub repository with the code for the project can be found <a href="https://github.com/2Manchu/MIPS-Processors">here.</a>