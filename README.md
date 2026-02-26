This repository contains benchmarks for the latest release of
the [DFT-FE code](https://sites.google.com/umich.edu/dftfe), targetting the OLCF GPU machines.

Release branch: https://github.com/dftfeDevelopers/dftfe/tree/release1.2

Current capablities of DFT-FE (release branch)
==========================================

    * Norm-conserving (ONCV, Troullier-Martins) pseudopotential and all-electron DFT calculations.

    * Fully periodic, semi-periodic and fully non-periodic boundary conditions, charged systems.


    * LDA, GGA, MGGA, DFT+U; Spin-polarization(collinear).

    * Geometry optimization with atomic forces and stresses computed using configurational forces.

    * Ab-initio Molecular Dynamics Capability (NVE, NVT)

    * Nudged Elastic Band based transition-state calculations

    * Band-structure, DOS, PDOS

The benchmarks are designed to cover most of the capabilities of the DFT-FE code. Please refer to the README file inside each benchmark directory for more detailed information regarding the benchmark, the associated accuracy studies, and any important notes for the user to setup similar or related calculations using DFT-FE.

List and brief description of the benchmarks
==========================================
* **benchmark1-BCCMo**: single point ground-state calculation on periodic system
