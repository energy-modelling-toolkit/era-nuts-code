# ERA-NUTS associated files

This repository contains the files associated to the [ERA-NUTS](https://doi.org/10.5281/zenodo.2650191) dataset, a set of time-series of meteorological variables based on [Copernicus Climate Change Service (C3S) ERA5 reanalysis](https://climate.copernicus.eu/climate-reanalysis). 

An example of the analysis that can be performed with ERA-NUTS is shown [in this video](https://youtu.be/zVeF8Dv6jlE).

**Important**: this dataset is still a work-in-progress, we will add more analysis and variables in the near-future. If you spot an error or something strange in the data please tell us [sending an email](mailto:matteo.de-felice@ec.europa.eu) or opening an Issue.

# Data
The data in NetCDF and CSV formats can be downloaded from the [Zenodo repository](https://doi.org/10.5281/zenodo.2650191) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2650191.svg)](https://doi.org/10.5281/zenodo.2650191)

# Example notebooks
In the folder `notebooks` there are two Jupyter notebooks which shows how to deal effectively with the NetCDF data in `xarray` and how to visualise them in several ways by using matplotlib or the [enlopy](https://github.com/kavvkon/enlopy) package. 

There are currently two notebooks: 
  - `exploring-ERA-NUTS`: it shows how to open the NetCDF files (with Dask), how to manipulate and visualise them. 
  - `ERA-NUTS-explore-with-widget`: explore interactively the datasets with [jupyter](https://jupyter.org/) and [ipywidgets](https://ipywidgets.readthedocs.io/en/stable/). (You need download the notebook locally)

The notebook `exploring-ERA-NUTS` is also available rendered as HTML. 

# Additional files

In the folder `additional files` there is a map showing the spatial resolution of the ERA5 reanalysis and a CSV file specifying the number of grid points with respect to each NUTS0/1/2 region.

# License

This dataset hosted in Zenodo is released under [CC-BY-4.0 license](https://creativecommons.org/licenses/by/4.0/). Code, and notebooks in this repository are released under MIT license.
