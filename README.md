SURFACE AIR TEMPERATURE - MODEL BIAS
====================================
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6656093.svg)](https://doi.org/10.5281/zenodo.6656093)   ![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)

![GitHub release](https://img.shields.io/github/v/release/edsml-mh1123/AR6-WGI-Figure?logo=github)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/edsml-mh1123/AR6-WGI-Figure/update)

## Disclaimer
Please note that figures in this repository may differ from those in the published version due to the editorial process. The repository contains the latest available versions prior to publication.

Figure number: 3.3
From the IPCC Working Group I Contribution to the Sixth Assessment Report: Chapter 3

![Figure 3.3](/figure/ar6_wg1_chap3_figure3_3_surface_temp_model_bias.png?raw=true)


## Contents

- [Contents](#contents)
- [Description](#description)
- [Installation](#installation)
  - [Option 1: Run on Binder (No Installation Needed)](#option-1-run-on-binder-no-installation-needed)
  - [Option 2: Local Installation](#option-2-local-installation)
- [Expected image path](#expected-image-path)
- [Software and hardware information](#software-and-hardware-information)
- [Publication sources](#publication-sources)
- [How to cite](#how-to-cite) 
  - [Figure Citation](#figure-citation)
  - [Repository Citation](#repository-citation)


## Description

The figure shows the annual-mean surface (2 m) air temperature (°C) for the 
period 1995–2014. (a) Multi-model (ensemble) mean constructed with one 
realization of the CMIP6 historical experiment from each model. (b) Multi-
model mean bias, defined as the difference between the CMIP6 multi-model mean
and the climatology of the Fifth generation of ECMWF atmospheric reanalyses 
of the global climate (ERA5). (c) Multi-model mean of the root mean square error
calculated over all months separately and averaged with respect to the 
climatology from ERA5. (d) Multi-model-mean bias as the difference between the 
CMIP6 multi-model mean and the climatology from ERA5. Also shown is the multi-
model mean bias as the difference between the multi-model mean of (e) high
resolution and (f) low resolution simulations of four HighResMIP models and the 
climatology from ERA5......


## Installation

### Option 1: Run on Binder (No Installation Needed)
You can quickly run this project in a live, interactive environment without any installation. Click the button below to launch the project on Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/edsml-mh1123/AR6-WGI-Figure/main)

This will automatically install the necessary dependencies and launch the Jupyter Notebooks in your browser.

### Option 2: Local Installation

If you prefer to run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/edsml-mh1123/AR6-WGI-Figure.git
   cd AR6-WGI-Figure

2. Create and activate the Conda environment:
   
```bash
conda env create -f environment.yml

conda activate fig3.3_env
```

3. Download the required data

Before running the rest of the Jupyter notebooks, you need to download the required data. Run the provided Python script to handle this:

```bash
cd data

python download_data.py
```


## Expected image path

- recipe_ipccwg1ar6ch3_atmosphere_YYYYMMDD_HHMMSS/plots/fig_3_3_cmip5/fig_3_3/model_bias_tas_annualclim_CMIP5.eps
- recipe_ipccwg1ar6ch3_atmosphere_YYYYMMDD_HHMMSS/plots/fig_3_3_cmip6/fig_3_3/model_bias_tas_annualclim_CMIP6.eps


## Software and Hardware Information

The software and hardware details for the system are included in the `system_description.yml` file. This file contains the following:

- **Software descriptions** (e.g., environment files for ESMValTool and pip)
- **Hardware descriptions** (e.g., machine used)


## Publication sources

Bock, L., Lauer, A., Schlund, M., Barreiro, M., Bellouin, N., Jones, C., Predoi, V., Meehl, G., Roberts, M., and Eyring, V.: Quantifying progress across different CMIP phases with the ESMValTool, Journal of Geophysical Research: Atmospheres, 125, e2019JD032321. https://doi.org/10.1029/2019JD032321


## How to cite

If you use this repository or any of its contents in your work, please cite it appropriately.

### Repository Citation
This repository includes a `CITATION.cff` file for citation. You can generate a citation in your preferred format using:

```bash
cffconvert --format bibtex
```

### Figure Citation
If you use Figure 3.3 from the IPCC report included in this repository, please cite it as:

Figure 3.2 in IPCC, 2021: Chapter 3. In: Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to 
the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [Eyring, V., N.P. Gillett, K.M. Achuta Rao, R. Barimalala,
 M. Barreiro Parrillo, N. Bellouin, C. Cassou, P.J. Durack, Y. Kosaka, S. McGregor, S. Min, O. Morgenstern, and Y. Sun, 2021: Human 
Influence on the Climate System. In Climate Change 2021: The Physical Science Basis. 
Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [Masson-Delmotte, V., 
P. Zhai, A. Pirani, S.L. Connors, C. Péan, S. Berger, N. Caud, Y. Chen, L. Goldfarb, M.I. Gomis, M. Huang, K. Leitzell, E. Lonnoy, 
J.B.R. Matthews, T.K. Maycock, T. Waterfield, O. Yelekçi, R. Yu, and B. Zhou (eds.)]. 
Cambridge University Press, Cambridge, United Kingdom and New York, NY, USA, pp. 423–552, doi: 10.1017/9781009157896.005 .]
