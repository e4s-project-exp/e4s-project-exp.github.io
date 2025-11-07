---
layout: single
title: Use E4S
permalink: /use/
classes: wide
sidebar:
  nav: "usemenu"
---

E4S offers multiple methods for deploying its collection of HPC and AI software packages. Below is an overview of these deployment options. Additional documentation is available from the side menu.

|Use Option | Description |
|-----------|-------------|
| From-Source Builds | E4S utilizes [Spack](https://spack.io), a flexible package manager, to facilitate building software directly from source. This allows users to customize builds for their specific systems. Instructions: [E4S Manual Installation Guide](https://e4s-project.github.io/manual-installation.html).
| Spack Build Cache | Pre-built binaries provided via Spack build caches enable faster installations without local compilation. More information on the [E4S About Page](https://e4s-project.github.io/about.html).
| Containers | E4S offers containerized versions of its software stack, compatible with Docker, Singularity, Shifter, and CharlieCloud. See the [Downloads page](/download.html) for available containers. Containers provide portable environments across systems. E4S containers are also available via [ParaTools Pro for E4S™](https://paratoolspro.com), including [AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-ozpychswxmldi). |
| Cloud Options |E4S can be deployed on Amazon Web Services (AWS) for scalable cloud-based HPC/AI workloads and Google Cloud Platform (GCP) with access to high-performance VMs and storage. 

{% include e4s-footer.html %}
