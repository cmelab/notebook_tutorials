# Notebook Tutorials

The conda environment used in these tutorials can be created using the following command:
```
conda create -yn cmelab -c conda-forge -c mosdef -c omnia 'python=3.7' matplotlib numpy parmed foyer freud fresnel gsd mbuild hoomd openbabel py3Dmol nodejs jupyterlab
```
Once your environment has been created, the environment can be activated and the interactive notebooks run using the following commands:
```
conda activate cmelab
jupyter lab
```

## Tutorials

1. The `opv_sim.ipynb` notebook demonstrates how to set up, run, and analyze a molecular dynamics simulation of a conjugated polymer. The following tools from [MoSDeF](https://mosdef.org/) and [Glotzer group](https://github.com/glotzerlab) are higlighted: 
[mbuild](https://mbuild.mosdef.org/en/stable/), [foyer](https://foyer.mosdef.org/en/latest/), [hoomd](https://hoomd-blue.readthedocs.io/en/stable/), [freud](https://freud.readthedocs.io/en/stable/fresnel), [fresnel](https://fresnel.readthedocs.io/en/stable/)
