# NoHNSo

<a href="https://manytools.org/hacker-tools/ascii-banner/"></a>
                                                                        
                                                                        
Welcome to NoHNSo, the Nonlinear Harmonic Navier-Stokes Solver. 

This tool is capable of solving the incompressible nonlinear Harmonic Navier-Stokes (HNS) equations for on a specified base flow. The implementation features blowing and suction capabilities and is formulated in generalized coordinates to incorporate smooth geometries as well as a (modifiable) embedded boundary method for sharp geometries. Nonlinear wave-triad interactions can be maintained and are converged in an iterative manner. A detailed description of the code containing derivation and implementation can be found in S. Westerbeek et al. (2023).

The following cases are currently implemented and tested:
  1. (Swept) flat plate boundary layer transition.
  2. Boundary layer transition featuring humps.
  3. Boundary layer transition featuring a sharp step.
  4. Boundary layer transition featuring blowing and suction at the wall.

NoHNSo was designed for use on local desktops and is currently not optimized for High-Performance Computing (HPC). However, NoHNSo runs on HPC environments as well when more demanding cases are performed.

Documentation detailing the use of the code (inputs, outputs, bug fixing etc.) can be found on https://svenwesterbeek.github.io/NoHNSo/.

#LicenseInfo?

