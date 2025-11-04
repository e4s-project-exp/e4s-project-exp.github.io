---
layout: single
title: "E4S Data & Visualization"
permalink: /e4s-dav/
classes: wide
sidebar:
  nav: "productfamiliesmenu"
---

This product family includes tools for I/O, data management, in situ and postprocessing analysis, and visualization. The aim is to move from raw simulation output to insight, without overwhelming overhead.

### Core libraries/tools  
- **HDF5**, netCDF, and parallel I/O back-ends (parallel HDF5, PnetCDF) for efficient structured data storage and access
- In-situ and coupling frameworks such as ADIOS, Catalyst, and Ascent for streaming analysis and visualization during runtime 
- Visualization engines like **ParaView**, **VisIt**, **VTK-m** for interactive or batch rendering and visual exploration 
- Data movement and indexing tools (e.g., GUFI, DataTransferKit, mochi/mercury, SicM) from the E4S catalog 

### Application needs addressed  
- High-throughput I/O from large-scale simulations with minimal interference  
- Compression, subsetting, streaming, and indexing of massive datasets  
- Runtime analytics, diagnostics, or visualization to avoid writing full dumps to disk  
- Visualization and rendering (2D/3D) for scientific insight, debugging, or publications  
- Data movement or metadata services across components or storage tiers  


Copyright © E4S a Series of LF Projects, LLC For web site terms of use, trademark policy and other project policies please see <https://lfprojects.org>.
