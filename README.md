# Quantum simulations

This is a landing page for my computational projects related to research in quantum many-body physics.

Below you will find a list of packages and libraries created to perform numerical simulations.
Each entry has a short description and cites the published works in which the code was used.
Since the projects were created for personal use, there is a lack of documentation, although the code should be readable, and some examples are provided.

**Work in progress:** Not all projects have been made public yet.

## PhD projects
 
* [ed-circuits](https://github.com/Hugo-loio/ed-circuits) - A Julia package for the exact diagonalization (ED) simulation of quantum circuits [^magic25][^mipt_mps24].
* [monitored-fermions](https://github.com/Hugo-loio/monitored-fermions) - A Python package for simulating monitored fermionic systems (both Gaussian and interacting) [^syk25][^purification23].
* [iMPS](https://github.com/Hugo-loio/iMPS) - A Python package for simulating infinite matrix product state (iMPS) evolution [^correlations25]
* [stim-deep-thermalization](https://github.com/Hugo-loio/stim-deep-thermalization) - A Python package to compute projected ensembles and frame potentials using the stabilizer formalism [^magic25].
* [spin-s-ed](https://github.com/Hugo-loio/spin-s-ed) - A small Python package for generating the spin operators and Hamiltonians for systems of generic spin-s particles [^syk25]

## Master's thesis project
* [TIM](https://github.com/Hugo-loio/TIM) - Topological Insulator Models (TIM) provides a C++ library for tight-binding models of topological insulators [^totai24].

## Extra tools
* [lasap](https://github.com/Hugo-loio/lasap) - A package with an interface for Python, Julia, and C++ to create a uniform data storage system with built-in post-processing tools.
Does not perform simulations, but aids in data handling, especially for parallelized tasks running in HPC clusters.

### List of relevant publications
[^magic25]: **H Lóio, G Lami, L Leone, M McGinley, X Turkeshi, J De Nardis,
"Quantum State Designs via Magic Teleportation",
[arXiv:2510.13950](https://doi.org/10.48550/arXiv.2510.13950) (2025)**

[^correlations25]: **H Lóio, G Cecile, S Gopalakrishnan3, G Lami1, J De Nardis
"Correlations, spectra, and entanglement transitions in ensembles of matrix product states",
[Phys. Rev. B 112, 035127](https://doi.org/10.1103/ymzz-923j) (2025)**

[^mipt_mps24]: **G Cecile, H Lóio, J De Nardis,
"Measurement-induced phase transitions by matrix product states scaling",
[Phys. Rev. Research 6, 033220](https://doi.org/10.1103/PhysRevResearch.6.033220) (2024)** 

[^syk25]: **A Tiutiakina, H Lóio, G Giachetti, J De Nardis, A De Luca,
"Field theory for monitored Brownian SYK clusters",
[Quantum 9, 1794.](https://doi.org/10.22331/q-2025-07-14-1794) (2025)**

[^purification23]: **H Lóio, A De Luca, J De Nardis, X Turkeshi,
"Purification timescales in monitored fermions",
[Physical Review B 108 (2), L020306](https://doi.org/10.1103/PhysRevB.108.L020306) (2023)**

[^totai24]: **H Lóio, M Gonçalves, P Ribeiro, EV Castro,
"Third-order topological insulator induced by disorder", 
[Physical Review B 109 (1), 014204.](https://doi.org/10.1103/PhysRevB.109.014204)**
