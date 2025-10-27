---
layout: single
title: "Infrastructure"
permalink: /e4s-infrastructure/
sidebar:
  nav: "productfamiliesmenu"
---

This product family includes build, packaging, deployment, and environment orchestration tools that underlie the entire software ecosystem. It ensures that the components from the other domains can be built, composed, deployed, and upgraded reliably.

### Core libraries/tools  
- **Spack** as the package manager and build system to manage versions, dependencies, and concretization   
- Container images and tooling (Docker, Singularity, Shifter) to distribute prebuilt stacks  
- **E4S-CL (Container Launch)** for seamlessly integrating MPI binaries with containerized runtime environments  
- Infrastructure for continuous integration, binary caching, build testing across architectures (CPU, GPU)  
- Cloud and platform environment support (AWS, Azure, Google Cloud, DOE leadership systems) to host full E4S stacks 

### Application needs addressed  
- Simplified build and deployment of complex, interdependent software stacks  
- Version and dependency management to avoid “dependency hell”  
- Portable binary delivery via containers or caches so users need not build from scratch  
- Robust testing across architectures to catch regressions early  
- Ability to upgrade component libraries while preserving compatibility  

Copyright © E4S a Series of LF Projects, LLC For web site terms of use, trademark policy and other project policies please see <https://lfprojects.org>.
