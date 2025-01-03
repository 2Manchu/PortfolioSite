---
title: "Multicore Operational Analysis Tooling" # Title of your project
date: 2024-02-07T10:15:15-06:00
weight: 1 # Order in which to show this project on the home page
external_link: "" # Optional external link instead of modal
resources:
    - src: poster.png
      params:
          weight: 0 # Optional weighting for a specific image in this project folder
draft: false
project_timeframe: "January 2024 - December 2024"
---

Iowa State CPRE senior design project, with Boeing as the client.

The increasing computational demand of modern avionics programs necessitates higher
performance hardware platforms to support them. Among the various avenues that exist, one
approach to achieving higher application performance is to utilize a multicore system. However,
incorporating such systems into safety-critical applications like avionics presents a unique set of
challenges when it comes to their airworthiness certification. The equipment manufacturer must
be able to prove that the system is resilient to performance degradation due to shared resource
“crosstalk” (also known as resource contention) from applications running on the platform’s
processor cores. Our team was tasked with building a test framework that would induce sufficient
resource contention on a target piece of hardware in order to facilitate more efficient airworthiness
testing of embedded Linux systems. Boeing presented our team with several requirements,
including processor architecture, system form factor, system resource partitioning approach, and
testing framework design. The final design utilizes a hardware platform incorporating the
recommended ARMv8 processor architecture, and supports the Xilinx PetaLinux framework,
allowing for streamlined system image revisions. The system image includes the Xen hypervisor,
which enables the user to partition execution of different programs to distinct processor cores and
quantify the effects of resource contention on worst-case program execution time. Our solution
includes a front end that allows for efficient collection of execution time metrics across a variety of
program types and resource contention methods. The current version of our system meets our
clients’ needs by providing them with a flexible framework that quantifies the effects of system
resource contention on program execution time. Given that our solution is open-source, future
developers may wish to make improvements in several areas, including analysis of contention
mitigation methods, inclusion of a graphical interface for testing, and refinements to the results
analysis tools. Overall, our solution is an important step in the landscape of modern multicore
systems analysis, and its open-source nature allows for its continued use and improvement.

A more in-depth project description, along with other detailed deliverables, can be found on our [senior design website.](https://sddec24-09.sd.ece.iastate.edu/) Additionally, the code is being hosted open-source on [GitHub.](https://github.com/2Manchu/MOAT)