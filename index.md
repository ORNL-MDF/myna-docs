---
title: Home
layout: default
nav_order: 1
---

# Myna

Myna is an open-source tool for connecting simulation pipelines with additive manufacturing process data.

Myna is a framework to facilitate simulation workflows for additive manufacturing
based on build data stored in well-defined data structures.
Myna was originally developed for the data structure maintained by ORNL
MDF's Peregrine tool for laser powderbed fusion.

Myna GitHub repository: [https://github.com/ORNL-MDF/Myna](https://github.com/ORNL-MDF/Myna)

## Citing

If you use Myna in your work, please
[cite this repository](https://zenodo.org/doi/10.5281/zenodo.13345124).
In addition, there is a preliminary work that introduces the concept of leverging the
digital thread for simulations and uses the precursor to Myna:

```tex
@article{Knapp2023DigitalThread,
   author = {Knapp, Gerald L. and Stump, Benjamin and Scime, Luke and Márquez Rossy, Andrés and Joslin, Chase and Halsey, William and Plotkowski, Alex},
   title = {Leveraging the digital thread for physics-based prediction of microstructure heterogeneity in additively manufactured parts},
   journal = {Additive Manufacturing},
   volume = {78},
   pages = {103861},
   ISSN = {2214-8604},
   DOI = {https://doi.org/10.1016/j.addma.2023.103861},
   year = {2023},
   type = {Journal Article}
}
```

The `resources/Peregrine` directory used for examples are from the publicly
available Peregrine v2023-10 dataset. If you use this data,
please cite:

```tex
@misc{Peregrine202310,
   author = {Scime, Luke and Snow, Zackary and Ziabari, Amir and Halsey, William and Joslin, Chase and Knapp, Gerry and Coleman, John and Peles, Amra and Graham, Sarah and Marquez Rossy, Andres and Duncan, Ryan and Paquit, Vincent},
   title = {A Co-Registered In-Situ and Ex-Situ Dataset from a Laser Powder Bed Fusion Additive Manufacturing Process (Peregrine v2023-10)},
   DOI = {https://doi.org/10.13139/ORNLNCCS/2008021},
   year = {2023},
   type = {Dataset}
}
```

## Acknowledgements

Myna was developed through the support of the Advanced Materials and Manufacturing
Technologies Office (AMMTO) of the U.S. Department of Energy  and used resources
at Oak Ridge National Laboratory Manufacturing Demonstration Facility. Additionally,
development used resources of the Compute and Data Environment for Science (CADES) at
the Oak Ridge National Laboratory, which is supported by the Office of Science of the
U.S. Department of Energy under Contract No. DE-AC05-00OR22725.
