# 2025 CCPBioSim Training Week materials

Presenters:

* Danny Cole
* Finlay Clark

## Agenda

### Half session - Wednesday Morning (10.30 AM - 12 PM?)

* Talk - Intro to OpenFF
* Notebook: [Parameterising small molecules with OpenFF](notebooks/small_molecule_parameterisation.ipynb)

### Half session - Wednesday Afternoon (1.00 PM - 3.00 PM?)

* Talk?
* Notebook: [Parameterisation, molecular dynamics, and basic trajectory analysis for a protein-ligand complex](notebooks/protein_ligand_complex_parameterisation_and_md.ipynb)

## Local installation

If there are any issues with the provided cloud-hosted JupyterHub instance, or to use these notebooks outside of the workshop hours, use a Python distribution (we recommend [Mambaforge](https://docs.openforcefield.org/en/latest/install.html#quick-install-guide)) and create an environment from the provided YAML file:

```shell
$ mamba env create --file environment.yaml
$ ...
$ mamba activate openff-env
```

## More resources

* Main [OpenFF docs](https://docs.openforcefield.org/en/latest/)
  * See "Projects" on the left for package-specific documentation
  * Ecosystem-wide [examples](https://docs.openforcefield.org/en/latest/examples.html)
* [SMIRNOFF](https://openforcefield.github.io/standards/standards/smirnoff/) specification
* [Discussions](https://github.com/orgs/openforcefield/discussions) - for general usage questions


## Acknowledgements

Most of this material is adapted from [the 2023 CCPBioSim training week workshop](https://github.com/openforcefield/ccpbiosim-2023).
