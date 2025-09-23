---
layout: single
title: "E4S Policies"
permalink: /policies/
---

# E4S Community Policies

**Version 1**

The [*Extreme-scale Scientific Software
Stack*](https://e4s-project.github.io/) (E4S) and its related SDKs are light-weight organizational elements intended to enhance collaboration and coordination across independently-developed products.

***E4S Membership Criteria***

The policies below are criteria for E4S membership. To qualify for E4S membership, a package must demonstrate compatibility with each of these policies. Under special circumstances, a package may be granted an exception to a policy.

**P1** *Spack-based Build and Installation* Each E4S member package supports a scriptable [*Spack*](https://spack.io/) build and installation in a way that is compatible with other E4S member packages.

**P2** *Minimal Validation Testing* Each E4S member package has at least one test executable through the [E4S validation test suite](https://github.com/E4S-Project/testsuite).

**P3** *Sustainability* All E4S compatibility changes will be sustainable and part of the regular development and release versions of the package.

**P4** *Documentation* Each E4S member package should have sufficient documentation to support installation and use.

**P5** *Product Metadata* Each team will provide product information via metadata in the [E4S DocPortal](https://e4s-project.github.io/DocPortal.html) format.

**P6** *Public Repository* Each package will have a public repository (e.g., GitHub or Bitbucket).

**P7** *Imported Software* Imported software must allow building/linking against outside copies to avoid conflicts.

**P8** *Error Handling* Each package adopts a consistent error handling system, returning error codes or exceptions, and proper exit statuses for CLI tools.

**P9** *Test Suite* Each package provides a test suite that does not require special privileges or commercial software.

## Future Revision E4S Community Policies

Policies under consideration for future versions (FP = future policy):

-   **FP1** Portability across OS, compilers, architectures, accelerators.
-   **FP2** Flexible test selection support for subsets of tests.
-   **FP3** Dependency version tracking via Spack.
-   **FP4** Memory testing (e.g., Valgrind support).
-   **FP5** Comprehensive test suite for user-level validation.
-   **FP6** Sufficient documentation to support installation, use, and development.

## Future Library Policies

FLP = future library policy

-   **FLP1** User-managed exception handling; no hardwired aborts or print statements.
-   **FLP2** User-managed I/O control with configurable outputs.
-   **FLP3** Proper namespacing of symbols, macros, and include files.
-   **FLP4** Memory leaks avoided by freeing all resources as soon as possible.

Created for [The E4S Project](https://e4s-project.github.io) by [Michael A. Heroux](https://maherou.github.io/)

[Copyright © E4S a Series of LF Projects, LLC, See <https://lfprojects.org> for terms of use and policies.
