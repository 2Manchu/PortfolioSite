---
title: "Multicore Operational Analysis Tooling" # Title of your project
date: 2024-02-07T10:15:15-06:00
weight: 1 # Order in which to show this project on the home page
external_link: "" # Optional external link instead of modal
resources:
    - src: bng.png
      params:
          weight: 0 # Optional weighting for a specific image in this project folder
draft: false
project_timeframe: "January 2024 - December 2024"
---

Iowa State CPRE senior design project, with Boeing as the client.

The aviation industry is adopting multicore systems to handle the demands of modern aviation technology. However, these systems can face interference issues that affect their performance, including the worst-case execution time for safety-critical tasks. To ensure the safety of avionics software, it's essential to examine and verify how interference impacts these systems. To address this, hardware and software providers are offering advanced partitioning technologies, allowing developers to allocate system resources effectively and minimize interference between applications running on separate processor cores. This project targets a specific ARM-based system-on-chip running the Xen hypervisor using both existing and custom-designed open-source tools to simulate interference scenarios provided by Boeing, aiming to enhance the robustness of avionics software on multicore architectures.

In this project, I have primarily acted as a project coordinator between the group and our contacts at Boeing, and contributed my knowledge of computer architecture to the selection of hardware and development of interference testing programs. As this project focuses heavily on our contribution to and usage of open-source software, a majority of the team's knowledge base was formed from the [Xen Project Wiki](https://wiki.xenproject.org/wiki/Main_Page) as well as exploration of various GitHub repositories relating to system stress and resource management.

A more in-depth project description, along with deliverables and up-to-date weekly progress reports can be found on our [senior design website.](https://sddec24-09.sd.ece.iastate.edu/)