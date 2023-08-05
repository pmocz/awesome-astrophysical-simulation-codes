# Awesome Astrophysical Simulation Codes [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome astrophysical simulation software

## Contents

- [Code List](#code-list)
- [Numerical Method](#numerical-method)
- [Physics](#physics)
- [High-Performance Features](#high-performance-features)
- [Contribute](#contribute)

## Code List

| Code      | Description | Lang. | Repo | Paper |
| --------- | ----------- | ----- |----- | ----- |
| [Athena++](https://www.athena-astro.app/) | Radiation GRMHD code and adaptive mesh refinement (AMR) framework. | ![](https://skillicons.dev/icons?i=cpp)   | [![](https://skillicons.dev/icons?i=github)](https://github.com/PrincetonUniversity/athena) | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2020ApJS..249....4S/abstract)  |
| [Arepo](https://arepo-code.org/) | Massively parallel moving Voronoi mesh cosmological simulation code. | ![](https://skillicons.dev/icons?i=c) | [![](https://skillicons.dev/icons?i=gitlab)](https://gitlab.mpcdf.mpg.de/vrs/arepo) | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2010MNRAS.401..791S/abstract) |
| [Cholla](https://github.com/cholla-hydro/cholla/wiki) | GPU-based hydro code. | ![](https://skillicons.dev/icons?i=cpp)  | [![](https://skillicons.dev/icons?i=github)](https://github.com/cholla-hydro/cholla) | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2016ascl.soft07006S/abstract) |
| [Dedalus](https://dedalus-project.org/) | Flexible framework for solving PDEs with modern spectral methods. | ![](https://skillicons.dev/icons?i=python) | [![](https://skillicons.dev/icons?i=github)](https://github.com/DedalusProject/dedalus) | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2020PhRvR...2b3068B/abstract)  |
| [Enzo](https://enzo-project.org/) | Adaptive Mesh Refinement Code for Astrophysics. | ![](https://skillicons.dev/icons?i=c)  | [![](https://skillicons.dev/icons?i=github)](https://github.com/enzo-project/enzo-dev) | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2014ApJS..211...19B/abstract) |
| [FLASH](https://flash.rochester.edu/site/flashcode/) | Adaptive Mesh Hydrodynamics Code for Modeling Astrophysical Thermonuclear Flashes. | ![](https://skillicons.dev/icons?i=fortran) |  | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2000ApJS..131..273F/abstract) |
| [Gadget](https://wwwmpa.mpa-garching.mpg.de/gadget4/) | Parallel cosmological N-body and SPH code. | ![](https://skillicons.dev/icons?i=c) | [![](https://skillicons.dev/icons?i=gitlab)](https://gitlab.mpcdf.mpg.de/vrs/gadget4) | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2022ascl.soft04014S/abstract) |
| [Gizmo](http://www.tapir.caltech.edu/~phopkins/Site/GIZMO.html) | Flexible, massively-parallel, multi-physics simulation code. | ![](https://skillicons.dev/icons?i=c) | [![](https://skillicons.dev/icons?i=gitlab)](https://bitbucket.org/phopkins/gizmo-public/src/master/) | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2015MNRAS.450...53H/abstract) |
| [Pencil](http://pencil-code.nordita.org/) | High-order finite-difference code for compressible hydrodynamic flows with magnetic fields and particles. | ![](https://skillicons.dev/icons?i=fortran) | [![](https://skillicons.dev/icons?i=github)](https://github.com/pencil-code/pencil-code) | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2010ascl.soft10060B/abstract) |
| [PHANTOM](https://phantomsph.github.io/) | Smoothed particle hydrodynamics and magnetohydrodynamics code for astrophysics. | ![](https://skillicons.dev/icons?i=fortran) | [![](https://skillicons.dev/icons?i=github)](https://github.com/danieljprice/phantom) | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2018PASA...35...31P/abstract) |
| [QUOKKA](https://github.com/quokka-astro/quokka) | First two-moment AMR radiation hydrodynamics on GPUs for astrophysics. | ![](https://skillicons.dev/icons?i=cpp) | [![](https://skillicons.dev/icons?i=github)](https://github.com/quokka-astro/quokka) | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2021ascl.soft10009W/abstract) |
| [RAMSES](https://bytebucket.org/rteyssie/ramses/wiki/ramses_ug.pdf?rev=b6b7fef09b8bfe0d1e27c7d0c9edd584ec12768e) | Code to model astrophysical systems, featuring self-gravitating, magnetized, compressible, radiative fluid flows. | ![](https://skillicons.dev/icons?i=fortran) | [![](https://skillicons.dev/icons?i=github)](https://github.com/miried/ramses) | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2002A%26A...385..337T/abstract) |
| [REBOUND](https://rebound.readthedocs.io/en/latest/) | Open-source multi-purpose N-body code. | ![](https://skillicons.dev/icons?i=c) | [![](https://skillicons.dev/icons?i=github)](https://github.com/hannorein/rebound) | [<img src="https://ui.adsabs.harvard.edu/styles/img/transparent_logo.svg" width="45" height="40">](https://ui.adsabs.harvard.edu/abs/2012A%26A...537A.128R/abstract) |

## Numerical Method

| Code      | Finite Difference | Finite Volume | Finite Element | Spectral | SPH | N-body | Eulerian | ALE | Lagrangian | AMR |
| --------- | :---------------: | :-----------: | :------------: | :------: | :-: | :----: | :------: | :-: | :--------: | :-: |
| Athena++  |                   | 🟩️️️️️            |                |          |     |        | 🟩️️️️️       |     |            | 🟩️️️️️  |
| Arepo     |                   | 🟩️️️️️            |                |          |     | 🟩️️️️️     |          | 🟩️️️️️  |            |     |
| Cholla    |                   | 🟩️️️️️            |                |          |     |        | 🟩️️️️️       |     |            |     |
| Dedalus   |                   |               |                | 🟩️️️️️       |     |        | 🟩️️️️️       |     |            |     |
| Enzo      |                   | 🟩️️️️️            |                |          |     |        | 🟩️️️️️       |     |            | 🟩️️️️️  |
| FLASH     |                   | 🟩️️️️️            |                |          |     |        | 🟩️️️️️       |     |            | 🟩️️️️️  |
| Gadget    |                   |               |                |          | 🟩️️️️️  | 🟩️️️️️     |          |     | 🟩️️️️️         |     |
| Gizmo     |                   | 🟩️️️️️            |                |          |     | 🟩️️️️️     |          |     | 🟩️️️️️         |     |
| Pencil    | 🟩️️️️️                |               |                |          |     |        | 🟩️️️️️       |     |            |     |
| PHANTOM   |                   |               |                |          | 🟩️️️️️  | 🟩️️     |          |     | 🟩️️️️️         |     |
| QUOKKA    |                   | 🟩️️️️️            |                |          |     |        | 🟩️️️️️       |     |            |     |
| RAMSES    |                   | 🟩️️️️️            |                |          |     | 🟩️️️️️     | 🟩️️️️️       |     |            | 🟩️️️️️  |
| REBOUND   |                   |               |                |          |     | 🟩️️️️️     |          |     |            |     |


## Physics

| Code      | Hydrodynamics | MHD | Radiation | Self-Gravity | General-Relativity |
| --------- | :-----------: | :-: |:--------: | :----------: | :----------------: |
| Athena++  | 🟩️️️️️            | 🟩️️️️️  | 🟩️️️️️        | 🟩️️️️️           | 🟩️️️️️                 |
| Arepo     | 🟩️️️️️            | 🟩️️️️️  | 🟩️️️️️        | 🟩️️️️️           |                    |
| Cholla    | 🟩️            |     | 🟩️        | 🟩️           |                    |
| Dedalus   | 🟩️            | 🟩️  |           | 🟩️           |                    |
| Enzo      | 🟩️            | 🟩️  | 🟩️        | 🟩️           |                    |
| FLASH     | 🟩️            | 🟩️  | 🟩️        | 🟩️           |                    |
| Gadget    | 🟩️            |     |           | 🟩️           |                    |
| Gizmo     | 🟩️            | 🟩️  | 🟩️        | 🟩️           |                    |
| Pencil    | 🟩️            | 🟩️  |           | 🟩️           |                    |
| PHANTOM   | 🟩️            |     |           | 🟩️           |                    |
| QUOKKA    | 🟩️️️️️            |     | 🟩️️️️️        | 🟩️️️️️           |                    |
| RAMSES    | 🟩️            | 🟩️  | 🟩️        | 🟩️           |                    |
| REBOUND   |               |     |           | 🟩️           |                    |


## High-Performance Features

| Code      | MPI | GPU |
| --------- | :-: | :-: |
| Athena++  | 🟩️️️️️  |     | 
| Arepo     | 🟩️️️️️  |     | 
| Cholla    | 🟩️️️️️  | 🟩️️️️️  |
| Dedalus   | 🟩️  |     | 
| Enzo      | 🟩️  |     | 
| FLASH     | 🟩️  |     | 
| Gadget    | 🟩️  |     | 
| Gizmo     | 🟩️  |     | 
| Pencil    | 🟩️  |     | 
| PHANTOM   | 🟩️  |     | 
| QUOKKA    | 🟩️  | 🟩️  |
| RAMSES    | 🟩️  |     | 
| REBOUND   | 🟩️  |     |


## Contribute

Contributions to the list are welcome! Contributing guidelines can be found in [contributing.md](contributing.md) 

<!---
[![My Skills](https://skillicons.dev/icons?i=python)](https://skillicons.dev)
[![made-with-cpp](https://img.shields.io/badge/Made%20with-C++-1f425f.svg)](http://www.cplusplus.com/)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![DOI](https://zenodo.org/badge/DOI/10.3847/1538-4365/ab929b.svg)](https://iopscience.iop.org/article/10.3847/1538-4365/ab929b)
-->
