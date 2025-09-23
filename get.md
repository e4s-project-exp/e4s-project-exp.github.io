---
layout: single
title: "Get E4S"
permalink: /get/
---

## Acquiring E4S Containers

The current E4S container offerings include Docker and Singularity
images capable of running on X86_64, PPC64LE, and AARCH64 architectures.
Our full E4S Release images are based on Ubuntu 22.04. In addition to
offering a full E4S image containing a comprehensive selection of E4S
software released on a bi-annual cycle, we also offer a set of minimal
base images suitable for use in CI pipelines.

Docker images are available on the [E4S Docker
Hub](https://hub.docker.com/u/ecpe4s).

Please see the [E4S 25.06 Release
Notes](https://oaciss.uoregon.edu/e4s/talks/E4S_25.06.pdf).

### Container Releases

-   [Docker Downloads - CPU only](https://hub.docker.com/r/ecpe4s/e4s-cpu/tags)
-   [Docker Downloads - CUDA](https://hub.docker.com/r/ecpe4s/e4s-cuda/tags)
-   [Docker Downloads - ROCm](https://hub.docker.com/r/ecpe4s/e4s-rocm/tags)
-   [Docker Downloads - OneAPI](https://hub.docker.com/r/ecpe4s/e4s-oneapi/tags)

### From source with Spack

Spack contains packages for all of the products listed in the E4S 25.06
Full Release category. General instructions for building software with
Spack can be found at the [Spack
website](https://spack.readthedocs.io/en/latest/).

### Note on Container Images

Container images contain binary versions of the Full Release packages
listed above. Full-featured GPU-enabled container images are available
from Dockerhub:
```
    # docker pull ecpe4s/e4s-cuda:25.06
    # docker pull ecpe4s/e4s-rocm:25.06
    # docker pull ecpe4s/e4s-oneapi:25.06
    # docker pull ecpe4s/e4s-cpu:25.06
```
### E4S Facility Deployment

- [NERSC](https://docs.nersc.gov/applications/e4s/)
- [OLCF](https://docs.olcf.ornl.gov/software/e4s.html)

### AWS EC2 Image

The E4S 25.06 release is also available on [AWS](http://aws.amazon.com/)
as an EC2 AMI with ID ami-0e752117cfa13cb9b in the US-West-2 (Oregon)
region.

Created for [The Extreme-scale Scientific Software Stack (E4S)
Project](https://e4s-project.github.io/) by [Michael A.
Heroux](https://maherou.github.io/)

[Attribution](https://e4s-project.github.io/credit.html)

Copyright © E4S a Series of LF Projects, LLC\
For web site terms of use, trademark policy and other project policies
please see <https://lfprojects.org>.
