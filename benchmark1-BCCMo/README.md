Description of the benchmark
==========================
This benchmark demonstrates a ground-state calculation with fully periodic boundary conditions on BCC Mo 4x4x4 supercell with a mono-vacancy, containing 431 Mo atoms (6034 electrons) ONCV pseudopotential from sg15 database, PBE exchange correlation, and Fermi-Dirac smearing temperature of 500 K are used. Ground-state energy, forces and stresses are computed and written to ``structureEnergyForcesGSData.txt'' (see dftfe-manual for description of the output format) 

* FE discretization commensurate with chemical accuracy (~1e-4 Ha/atom in energy, ~1e-4 Ha/Bohr in ionic forces and ~1e-6 Ha/Bohr^3 in cell stresses). 

* 2, 4, and 8 GPU nodes are used
