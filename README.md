# 2026 CCPBioSim Training Week materials

[![CI](https://github.com/openforcefield/ccpbiosim-workshop/actions/workflows/ci.yaml/badge.svg)](https://github.com/openforcefield/ccpbiosim-workshop/actions/workflows/ci.yaml)

These tutorials were delivered at the 2026 CCPBioSim training week, but are suitable for self-guided learning.

Presenters:

* Danny Cole
* Finlay Clark

## Materials

We recommend you view the materials in the following order:

* Talk: [Intro to OpenFF](talk-cole-openFFintro.pdf)
* Notebook: [Parameterising small molecules with OpenFF](notebooks/small_molecule_parameterisation.ipynb)
* Notebook: [Parameterisation, molecular dynamics, and basic trajectory analysis for a protein-ligand complex](notebooks/protein_ligand_complex_parameterisation_and_md.ipynb)

Answers to most exercises are given in the [notebooks_with_solutions directory](notebooks_with_solutions).

## Local installation

To use these notebooks on your local machine, we recommend using [mamba](https://docs.openforcefield.org/en/latest/install.html#quick-install-guide) to create an environment from the provided YAML file:

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

Most of the material for the notebook [Parameterising small molecules with OpenFF](notebooks/small_molecule_parameterisation.ipynb) was adapted from the [2023 CCPBioSim Workshop Open Force Field Sessions](https://github.com/openforcefield/ccpbiosim-2023?) created by Matt Thompson and Jeff Wagner, as well as the [Simulating Post-Translationally Modified Proteins with the OpenFF Rosemary Alpha Workshop](https://github.com/openforcefield/2026-virtual-workshops/blob/main/ptm/ptm-workshop.ipynb) from Ashley Mitchell.

Most of the material for the notebook [Parameterisation, molecular dynamics, and basic trajectory analysis for a protein-ligand complex](notebooks/protein_ligand_complex_parameterisation_and_md.ipynb) was adapted from the OpenFF [toolkit showcase](https://docs.openforcefield.org/en/latest/examples/openforcefield/openff-toolkit/toolkit_showcase/toolkit_showcase.html) and the [ProLIF Ligand-protein MD tutorial](https://prolif.readthedocs.io/en/latest/notebooks/md-ligand-protein.html#ligand-protein-md).
