# UVIT notebooks

I am trying to compile a few Jupyter notebooks related to UVIT analysis. I hope that it may be helpful. Click on "Launch binder" badge below to load the notebooks present in this repository for an online interactive analysis.

 [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/prajwel/UVIT_notebooks/HEAD)


## 1. Search your target among existing UVIT pointings 
The first one deals with how to search your source of interest among the already observed list of targets. A list has been compiled with Observation IDs and pointing coordinates in RA and DEC. This list can be accessed at `UVIT_pointings.txt` (I will try to keep the list updated).

The Jupyter notebook with the python script to do the search can be found at `search_your_target_among_existing_UVIT_pointings.ipynb`.

## 2. Can UVIT observe your field of interest?
If your field of interest is not already observed by UVIT in the desired filters/gratings, you can submit a new AstroSat proposal. But you must first check UVIT can safely observe your field. The notebook `UVIT_VIS_UV_safety_check.ipynb` shows how to do this. 

*More notebooks will be added soon....*