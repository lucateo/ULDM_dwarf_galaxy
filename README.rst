Ultra-Light Dark Matter Simulations and Stellar Dynamics: Tension in Dwarf Galaxies for $m < 10^{-25}$ eV
==============================

This repository hosts the programs needed to obtain some of the results showed in the paper
**Ultra-Light Dark Matter Simulations and Stellar Dynamics: Tension in Dwarf Galaxies for $m < 10^{-25}$ eV** by Luca Teodori, Andrea Caputo and Kfir Blum.

Abstract
--------
We present numerical simulations of dark matter and stellar dynamics in Ultra Light Dark Matter halos 
tailored to mimic dwarf galaxies. For dark matter particle mass $m \approx 10^{-22}$ eV, dynamical heating 
causes the half-light radius to over-shoot surface brightness data of the Fornax galaxy. 
For $m\approx 10^{-21}$ eV, soliton core formation leads to a velocity dispersion peak incompatible 
with kinematics data. Extending the analysis to the Carina and Leo II galaxies, the tension persists up 
to $m \approx 5\times 10^{-21}$ eV. A caveat in our analysis is the omission of stellar self-gravity. This would not change 
dynamics today, but could affect extrapolation back in time if the stellar body was more compact in the past. 

Notebooks
---------
For reproducing the main results of the paper, we have data available in the ``out_stars`` folder. 
Due to heavy size of star data, we uploaded only one example of a simulation. Other data are available upon request.
To use those data, we prepared the jupyter notebook:

* ``uldm_stars_notebook.ipynb``: code related to reproduce the main figures of our work.

The ULDM code used to do the simulations is available upon request.

Authors
-------
- Luca Teodori; luca.teodori@weizmann.ac.il
- Andrea Caputo; andrea.caputo@cern.ch
- Kfir Blum; kfir.blum@weizmann.ac.il

Citations
---------
To cite our work::

  @article{Teodori:2025rul,
      author = "Teodori, Luca and Caputo, Andrea and Blum, Kfir",
      title = "{Ultra-Light Dark Matter Simulations and Stellar Dynamics: Tension in Dwarf Galaxies for $m < 5\times10^{-21} $ eV}",
      eprint = "2501.07631",
      archivePrefix = "arXiv",
      primaryClass = "astro-ph.GA",
      month = "1",
      year = "2025"
  }