# Notebook Tutorials

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cmelab/notebook_tutorials/master?filepath=index.ipynb) [![Build and Cache Image](https://github.com/cmelab/notebook_tutorials/workflows/Build%20and%20Cache%20Image/badge.svg?branch=master)](https://github.com/cmelab/notebook_tutorials/actions?query=branch%3Amaster+workflow%3A%22Build+and+Cache+Image%22)

Use the binder above to use these notebooks in your browser.

Or if you'd like to run these notebooks on your local machine, the conda environment used in these tutorials can be created using the following command:
```
conda env create -f environment.yml
```
Once your environment has been created, the environment can be activated and the interactive notebooks run using the following commands:
```
conda activate cmelab
jupyter lab
```

## Tutorials
These tutorials highlight the following tools from [MoSDeF](https://mosdef.org/) and [Glotzer group](https://github.com/glotzerlab): 
[mbuild](https://mbuild.mosdef.org/en/stable/), [foyer](https://foyer.mosdef.org/en/latest/), [hoomd](https://hoomd-blue.readthedocs.io/en/stable/), [freud](https://freud.readthedocs.io/en/stable/fresnel), [fresnel](https://fresnel.readthedocs.io/en/stable/)

1. Initializing a system to a specific density - `MD_density.ipynb` This tutorial will explain some of the common pitfalls of initializing a system at high density and how to overcome them by using a "shrink step."
1. Radial Distribution Function - `radial-distribution-function.ipynb` demonstrates how to calculate the RDF and shows how the temperature affects the system
1. Organic Photovoltaic Simulation - `opv_sim.ipynb` demonstrates how to set up, run, and analyze a molecular dynamics simulation of a conjugated polymer. 
1. Temperature/Thermostat - (WIP) `temperature-thermostat.ipynb`
