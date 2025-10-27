---
layout: single
title: "Programming Systems & Tools"
permalink: /e4s-programming-systems/
sidebar:
  nav: "productfamiliesmenu"
---


### Overview  
This product family encompasses compilers, runtime systems, and portability or abstraction layers that mediate between application code and hardware details — especially when targeting multiple CPU and GPU architectures.

### Core libraries/tools  
- LLVM compiler infrastructure, including Fortran front ends (e.g. Flang)  
- Portability layers such as **Kokkos** (and complementary frameworks like RAJA) to abstract over CUDA, HIP, SYCL, or backend-specific implementations  
- MPI (Open MPI, MPICH) and related communication/runtime layers  
- Task parallel and PGAS systems (e.g. Legion, PaRSEC, UPC++) 

### Application needs addressed  
- Performance portability: write algorithms once (e.g. in Kokkos) and run efficiently across CPU/GPU platforms  
- Maintaining a modern, hardware-aware compiler and runtime toolchain that can exploit vectorization, offload, and memory hierarchies  
- Managing parallelism, communication, and data locality abstractions, so that application developers need not hand‐tune device glue code  
- Easing migration when the hardware or programming model evolves  


Copyright © E4S a Series of LF Projects, LLC For web site terms of use, trademark policy and other project policies please see <https://lfprojects.org>.
