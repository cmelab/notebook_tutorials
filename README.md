# Notebook Tutorials

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cmelab/notebook_tutorials/master)

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

1. Intro to Molecular Dynamics - (WIP)
1. Radial Distribution Function - 
1. Organic Photovoltaic Simulation - The `opv_sim.ipynb` notebook demonstrates how to set up, run, and analyze a molecular dynamics simulation of a conjugated polymer. The following tools from [MoSDeF](https://mosdef.org/) and [Glotzer group](https://github.com/glotzerlab) are higlighted: 
[mbuild](https://mbuild.mosdef.org/en/stable/), [foyer](https://foyer.mosdef.org/en/latest/), [hoomd](https://hoomd-blue.readthedocs.io/en/stable/), [freud](https://freud.readthedocs.io/en/stable/fresnel), [fresnel](https://fresnel.readthedocs.io/en/stable/)
