[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5979561.svg)](https://doi.org/10.5281/zenodo.5979561)

This folder contains all the codes needed to reproduce the results of the article 

"Quantifying the impact of ecological memory on the dynamics of interacting communities" 

Moein Khalighi, Guilhem Sommeria-Klein, Didier Gonze, Karoline Faust, Leo Lahti 

Link to the preprint: https://www.biorxiv.org/content/10.1101/2021.09.01.458486v1.abstract

DOI for the code: 10.5281/zenodo.5979561

The code is available with BSD 2-Clause License.

Correspondence: moein.khalighi@utu.fi

Each figure can be generated by running file Main.m in the folder with the corresponding name. In addition, one can generate a new result with arbitrary settings by using files *3Species* and *Nspecies*, changing the inputs in the Inputs part of Main.m, and following the instructions inside the code.

Furthermore, we have recently developed an open-source Julia package, *FdeSolver.jl*, to numerically solve ordinary differential equations with fractional derivatives, which can be used to incorporate memory effects into many models. For the installation, instruction, and further information, see the Readme file of the package and the example described in https://github.com/JuliaTurkuDataScience/FdeSolver.jl/blob/main/examples/MicrobialCommunities.jl showing how to implement the solver for the Gonze model studied in this paper.
