---
layout: home
title: "E4S: An HPC-AI Software Ecosystem for Science"
excerpt: "Empowering scientific computing with curated libraries and tools."
layout: splash # Default: home, but that includes a list of posts
classes: wide
header:
#   overlay_color: "#000"
#  overlay_filter: "0.60"
  overlay_filter: rgba(0, 146, 202, 0.75) # Same color as "air" skin footer
  overlay_image: /assets/images/e4s-logo.jpg
permalink: "/"
---


Welcome to **E4S**, a software **ecosystem for science**, a trusted source for curated, high-quality scientific libraries and tools designed for advanced computing applications and platforms.

**E4S is a community effort to provide and support an open-source software ecosystem for science**. E4S provides a **curated collection of scientific libraries and tools (packages) that form the foundation for hundreds of the world's most advanced scientific applications.**
                            
**E4S packages support developing, deploying and running scientific applications on high-performance computing (HPC) and AI platforms** sponsored by the **US Department of Energy (DOE) Office of Advanced Scientific Computing Research**.  E4S is also used as a foundation for applications on leadership-class computing systems at the **US Department of Defense, US National Science Foundation, and other federal agencies.**  It is used on numerous high-performance computing systems at universities and at collaborating international organizations.  
 
**E4S provides from-source builds, containers, and pre-installed versions of a [broad collection of HPC and AI software packages (E4S 25.06 release announcement)](news/NEWS_RELEASE_E4S_25.06.pdf)** E4S includes contributions from many organizations, including national laboratories, universities, and industry.  E4S is one of the key legacies of the [US Exascale Computing Project (ECP)](https://www.exascaleproject.org), a collaborative effort of the US Department of Energy Office of Advanced Scientific Computing Research and the National Nuclear Security Administration.

### Purpose

E4S exists to accelerate the development, deployment and use of HPC-AI software, lowering the barriers for HPC-AI users. E4S represents one of the largest collections of performance-portable GPU-enabled libraries and tools, supporting users of NVIDIA, AMD, and Intel GPUs in addition to Intel, AMD and Arm CPUs.  E4S provides containers and turn-key, from-source builds of more than 120 popular HPC-AI products.  E4S products include programming models, such as MPI and Kokkos; development tools such as HPCToolkit, TAU and PAPI; math libraries such as PETSc and Trilinos; Data and Viz tools such as HDF5 and Paraview; and AI products such as JAX, PyTorch, TensorFlow, and Horovod.  The entire portfolio is tested and validated on a variety of platforms, from laptops to supercomputers, providing confidence for users to upgrade with each E4S release.

### Approach
                          
E4S relies on <a href="https://spack.io">Spack</a>, a powerful package management platform widely used in the HPC-AI community. By using Spack as the package manager and providing containers of pre-built binaries for Docker, Singularity, Shifter and CharlieCloud, E4S enables the flexible use and testing of a <a href="DocPortal.html"> large collection of reusable HPC-AI software packages</a>.  E4S also provides a set of Software Development Kits (SDKs) to promote interoperability between products.  Finally, E4S products provide performance portability across a wide range of CPU and GPU architectures, including Intel, AMD, and Arm CPUs, and NVIDIA, AMD, and Intel GPUs using the Kokkos programming model and similar approaches, the MPI programming model via multiple MPI implementations, and new emerging language parallel programming support in the LLVM ecosystem.

### Platforms

E4S packages build on most computer systems, from laptops to supercomputers. E4S is available on all major leadership platforms at the US Department of Energy facilities, including the Exascale systems, <a href="https://www.olcf.ornl.gov/olcf-resources/compute-systems/frontier/">Frontier</a> at Oak Ridge National Lab, and <a href="https://www.alcf.anl.gov/aurora">Aurora</a>, at Argonne National Lab (capable of a billion-billion operations per second). E4S is also available in containers from DockerHub and on cloud platforms, such as AWS, Azure, and Google Cloud.  <a href="https://paratoolspro.com">ParaTools Pro for E4S&trade;</a> is a commercial version of E4S that provides additional support and services for E4S users including availability on <a href="https://aws.amazon.com/marketplace/search/results?searchTerms=ParaTools+Pro">AWS</a>.

### Testing

The E4S software distribution is tested regularly on a variety of platforms, from Linux clusters to leadership platforms. E4S is tested on all major leadership platforms at the US Department of Energy facilities, including the Exascale systems, Frontier at Oak Ridge National Lab, and Aurora, at Argonne National Lab. E4S is also tested on cloud platforms, such as AWS, Azure, and Google Cloud.  Finally, E4S is ported and tested on the <a href="https://systems.nic.uoregon.edu/internal-wiki/index.php?title=Category:Servers" >Frank system</a> at the University of Oregon.

[Learn more](/about/)

Copyright © E4S a Series of LF Projects, LLC For web site terms of use, trademark policy and other project policies please see <https://lfprojects.org>.
