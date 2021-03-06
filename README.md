# UVIT notebooks

I am trying to compile a few Jupyter notebooks related to UVIT analysis in hopes that it may be helpful. Click on the "launch binder" badge below to load the notebooks present in this repository for online interactive analysis.

 [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/prajwel/UVIT_notebooks/HEAD)


## 1. Search your target among existing UVIT pointings 
The first one deals with how to search your source of interest among the already observed list of targets. A list has been compiled with Observation IDs and pointing coordinates in RA and DEC. This list can be accessed at [UVIT_pointings.txt](\UVIT_pointings.txt) (I will try to keep the list updated). The Jupyter notebook with the python script to do the search can be found at [notebook1_search_your_target_among_existing_UVIT_pointings.ipynb](/notebook1_search_your_target_among_existing_UVIT_pointings.ipynb).

## 2. Can UVIT observe your field of interest? Find out with CanUVIT!
If your field of interest is not already observed by UVIT in the desired filters/gratings, you can submit a new AstroSat proposal. But you should first check if UVIT can safely observe your field. The notebook [notebook2_UVIT_VIS_UV_safety_check.ipynb](/notebook2_UVIT_VIS_UV_safety_check.ipynb) shows how to do this.

## 3. Overview of UVIT Level2 data from Astrobrowse
The notebook [notebook3_How_to_download_UVIT_data_from_ISSDC_Astrobrowse.ipynb](/notebook3_How_to_download_UVIT_data_from_ISSDC_Astrobrowse.ipynb) walks you through accessing UVIT Level2 data from ISSDC Astrobrowse website. It also provides an overview of the Level2 data.


*More notebooks will be added soon....*