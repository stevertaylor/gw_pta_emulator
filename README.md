# gw_pta_emulator
A notebook and data associated with the paper ["Constraints On The Dynamical Environments Of Supermassive Black-hole Binaries Using Pulsar-timing Arrays"](https://arxiv.org/abs/1612.02817 "Constraints On The Dynamical Environments Of Supermassive Black-hole Binaries Using Pulsar-timing Arrays"), Taylor, S. R., Simon, J., Sampson, L., arXiv:1612.02817 (2016). 

Users can read in GW characteristic strain spectra from black-hole population simulations, re-bin for their own observing baseline, and construct new spectra. The notebook then allows the user to train a Gaussian process to emulate the spectral behavior at all frequencies across the astrophysical parameter space of supermassive black-hole binary environments.

## Requirements

* Standard python installation 
  * matplotlib, numpy, math, sys, os, glob, cPickle)
* Extra packages
  * george (can be cloned and installed from https://github.com/dfm/george)
  * emcee (can be cloned and installed from https://github.com/dfm/emcee)
  * corner (can be cloned and installed from https://github.com/dfm/corner.py)
  
## Usage
The notebook can be started from the command line using `jupyter notebook gp4ptas.ipynb`. Cells are excecuted in serial order using Shift+Enter.
