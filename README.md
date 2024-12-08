# libra-run-template

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14317601.svg)](https://doi.org/10.5281/zenodo.14317601)


This is a template repository for experimental runs of LIBRA.

Create a conda environment

```
conda env create -f environment.yml
```

## Todo list:
- [x] [Link to Zenodo](https://zenodo.org/)
- [x] Add Zenodo badge with DOI
- [ ] Add LSC data to [`data/tritium_detection`](data/tritium_detection)
- [ ] Add neutron detection data to [`data/neutron_detection`](data/neutron_detection)
- [ ] Add OpenMC model to [`analysis/neutron`](analysis/neutron)
- [ ] Add Tritium model to [`analysis/tritium`](analysis/tritium)
- [ ] Add the right version tags to [`environment.yml`](environment.yml)
- [ ] Add information to the README (info about the run)
- [ ] Add [binder](https://mybinder.org/) badge
- [ ] Update [CI workflows](.github/workflows)