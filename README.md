[![github](https://img.shields.io/badge/GitHub-tarrla%2Flare3d_cfd_tools-blue.svg?style=flat)](https://github.com/tarrla/lare3d_cfd_tools)
[![ADS](https://img.shields.io/badge/NASA%20ADS-ApJS%2C%20V270%2C%202%2C%2030-red)](https://ui.adsabs.harvard.edu/abs/2024ApJS..270...30T/abstract)

# lare3d_cfd_tools

Routines for reading, writing, and performing other analysis on the standard *.cfd files generated 
by the version 2 of the LaRe3D MHD code. Note that LaRe version >=3 use a different output format, *.SDF files.

## References
Original LaRe paper by Arber+2001, JCP: 
https://ui.adsabs.harvard.edu/abs/2001JCoPh.171..151A/abstract

The current CFD reader is heavily adapted from original code at:
https://raw.githubusercontent.com/mbareford/rs-shock-heating-paper/master/scripts/python/lare3d_cfd.py

The CFD writer contained herein was subsequently adpted from the (new) CFD reader by N.Dylan Kee (NSO, now GSFC).

Most recent academic website for LARE:
https://warwick.ac.uk/fac/sci/physics/research/cfsa/people/tda/larexd/

Github repository (version 4 of LaRe, also using *.SDF files)
https://github.com/Warwick-Plasma/Lare3d 

Much of this code was written in support of developing data-driven simulations using LaRe, as described in
Tarr+2024 ApJS 270, 30.  If you are so inclined, please cite (or even read!) the following:

    DOI: 10.3847/1538-4365/ad0e0c
    ADS: https://ui.adsabs.harvard.edu/abs/2024ApJS..270...30T/abstract

Eventually it would be useful to change this from a collection of functions to an actual python Class.
