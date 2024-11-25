SURFACE AIR TEMPERATURE - MODEL BIAS
====================================
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6656093.svg)](https://doi.org/10.5281/zenodo.6656093)

Figure number: 3.3
From the IPCC Working Group I Contribution to the Sixth Assessment Report: Chapter 3

![Figure 3.3](/ar6_wg1_chap3_figure3_3_surface_temp_model_bias.png?raw=true)


Description:
------------
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


INSTALLATION:
------------
To set up this project, follow these steps:

1. Clone the repository

```python
git clone https://github.com/edsml-mh1123/AR6-WGI-Figure.git

```

2. Install the required packages
   
```bash
pip install -r requirements.txt

```

3. Download the required data

Before running the rest of the Jupyter notebooks, you need to download the required data. Run the provided Python script to handle this:

```bash
cd data

python download_data.py
```
This contains 4 datasets: 

- **Model Data:**
  - Ferguson_fire_train: Training data obtained from wildfire simulations.
  - Ferguson_fire_test: Testing data obtained from different simulations.
  - Ferguson_fire_background: Model simulation data used for data assimilation.

- **Satellite Data:**
  - Ferguson_fire_obs: Observation data at different days after ignition (one trajectory).


Final Data: 
--------------------
**Definition:** This is the final dataset prepared for visualization. It is derived from the processed data and contains only the variables and structure necessary for creating specific plots or graphs.

fig3.2b_1pctCO2_CMIP5.csv, fig3.2b_1pctCO2_CMIP5_ensemble_mean.csv, fig3.2b_1pctCO2_CMIP6.csv,fig3.2b_1pctCO2_CMIP6_ensemble_mean.csv

Other data: 
--------------------
Definition: Please provide a clear explanation of the relationship between these datasets and **Final Data**, along with the relevant code.

1. WCRP CMIP6: University of Arizona - Department of Geosciences (UA) MCM-UA-1-0 model output for the "ssp585" experiment
(https://catalogue.ceda.ac.uk/uuid/1de487e6c3c943c3967cd2d8bdef8b72/)

WCRP CMIP6 data can be downloaded via `download_data.py` and the final data is obtained by running the `data_processing.py`.

2. xxxxx

3. xxxxx

Expected image path:
--------------------
- recipe_ipccwg1ar6ch3_atmosphere_YYYYMMDD_HHMMSS/plots/fig_3_3_cmip5/fig_3_3/model_bias_tas_annualclim_CMIP5.eps
- recipe_ipccwg1ar6ch3_atmosphere_YYYYMMDD_HHMMSS/plots/fig_3_3_cmip6/fig_3_3/model_bias_tas_annualclim_CMIP6.eps


Software description:
---------------------
- ESMValTool environment file: [IPCC_environments/ar6_newcore_lisa_conda_environment.yml](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/main/IPCC_environments/ar6_newcore_lisa_conda_environment.yml)
- pip file: [IPCC_environments/ar6_newcore_lisa_pip_environment.txt](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/main/IPCC_environments/ar6_newcore_lisa_pip_environment.txt)


Hardware description:
---------------------
Machine used: Mistral


Author list:
------------
- Bock, L.: DLR, Germany; lisa.bock@dlr.de
- Bellouin, N.: University of Reading, UK 
- Eyring, V.: DLR., Germany


Publication sources:
--------------------
Bock, L., Lauer, A., Schlund, M., Barreiro, M., Bellouin, N., Jones, C., Predoi, V., Meehl, G., Roberts, M., and Eyring, V.: Quantifying progress across different CMIP phases with the ESMValTool, Journal of Geophysical Research: Atmospheres, 125, e2019JD032321. https://doi.org/10.1029/2019JD032321


LICENCE:
---------------------
This project is licensed under the MIT Licence. See the [LICENCE](https://github.com/edsml-mh1123/AR6-WGI-Figure/blob/main/LICENSE) file for details. 


How to cite:
---------------------
Figure 3.2 in IPCC, 2021: Chapter 3. In: Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to 
the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [Eyring, V., N.P. Gillett, K.M. Achuta Rao, R. Barimalala,
 M. Barreiro Parrillo, N. Bellouin, C. Cassou, P.J. Durack, Y. Kosaka, S. McGregor, S. Min, O. Morgenstern, and Y. Sun, 2021: Human 
Influence on the Climate System. In Climate Change 2021: The Physical Science Basis. 
Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change [Masson-Delmotte, V., 
P. Zhai, A. Pirani, S.L. Connors, C. Péan, S. Berger, N. Caud, Y. Chen, L. Goldfarb, M.I. Gomis, M. Huang, K. Leitzell, E. Lonnoy, 
J.B.R. Matthews, T.K. Maycock, T. Waterfield, O. Yelekçi, R. Yu, and B. Zhou (eds.)]. 
Cambridge University Press, Cambridge, United Kingdom and New York, NY, USA, pp. 423–552, doi: 10.1017/9781009157896.005 .]
