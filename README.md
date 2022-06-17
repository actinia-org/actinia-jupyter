# actinia tutorial: Jupyter notebooks

Actinia is an open source REST API for scalable, distributed, high performance processing of geographical data that uses GRASS GIS for computational tasks.
It provides a REST API to process satellite images, time series of satellite images, arbitrary raster data with geographical relations and vector data.

The Jupyter notebooks included here are based on the [actinia tutorial](https://mundialis.github.io/actinia_core/).
This repository offers the tutorial chapters as notebooks, for local usage or to run via Google Colab or binder in your browser.

* Introduction:
    * [original tutorial](https://mundialis.github.io/actinia_core/introduction/) | [Jupyter notebook](https://github.com/mundialis/actinia-jupyter/blob/main/notebooks/actinia_introduction.ipynb)
    * [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mundialis/actinia-jupyter/blob/main/notebooks/actinia_introduction.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mundialis/actinia-jupyter/7fa1c793cb00e59a0abaa4c97b1d65710e4d47fa?urlpath=lab%2Ftree%2Fnotebooks%2Factinia_introduction.ipynb)
* actinia database access:
    * [original tutorial](https://mundialis.github.io/actinia_core/tutorial_data_access/) | [Jupyter notebook](https://github.com/mundialis/actinia-jupyter/blob/main/notebooks/actinia_database_access.ipynb)
    * [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mundialis/actinia-jupyter/blob/main/notebooks/actinia_database_access.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mundialis/actinia-jupyter/7fa1c793cb00e59a0abaa4c97b1d65710e4d47fa?urlpath=lab%2Ftree%2Fnotebooks%2Factinia_database_access.ipynb)
* Time-series (STRDS) sampling:
    * [original tutorial](https://mundialis.github.io/actinia_core/tutorial_strds_sampling/) | [Jupyter notebook](https://github.com/mundialis/actinia-jupyter/blob/main/notebooks/actinia_strds_sampling.ipynb)
    * [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mundialis/actinia-jupyter/blob/main/notebooks/actinia_strds_sampling.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mundialis/actinia-jupyter/7fa1c793cb00e59a0abaa4c97b1d65710e4d47fa?urlpath=lab%2Ftree%2Fnotebooks%2Factinia_strds_sampling.ipynb)
* Landsat NDVI computation:
    * [original tutorial](https://mundialis.github.io/actinia_core/tutorial_landsat_ndvi/) | [Jupyter notebook](https://github.com/mundialis/actinia-jupyter/blob/main/notebooks/actinia_landsat_ndvi.ipynb)
    * [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mundialis/actinia-jupyter/blob/main/notebooks/actinia_landsat_ndvi.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mundialis/actinia-jupyter/7fa1c793cb00e59a0abaa4c97b1d65710e4d47fa?urlpath=lab%2Ftree%2Fnotebooks%2Factinia_landsat_ndvi.ipynb)
* Sentinel-2 NDVI computation:
    * [original tutorial](https://mundialis.github.io/actinia_core/tutorial_sentinel2_ndvi/) | [Jupyter notebook](https://github.com/mundialis/actinia-jupyter/blob/main/notebooks/actinia_sentinel2_ndvi.ipynb)
    * [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mundialis/actinia-jupyter/blob/main/notebooks/actinia_sentinel2_ndvi.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mundialis/actinia-jupyter/7fa1c793cb00e59a0abaa4c97b1d65710e4d47fa?urlpath=lab%2Ftree%2Fnotebooks%2Factinia_sentinel2_ndvi.ipynb)
* User defined processing:
    * [original tutorial](https://mundialis.github.io/actinia_core/tutorial_process_chain/) | [Jupyter notebook](https://github.com/mundialis/actinia-jupyter/blob/main/notebooks/actinia_process_chain.ipynb)
    * [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mundialis/actinia-jupyter/blob/main/notebooks/actinia_process_chain.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mundialis/actinia-jupyter/7fa1c793cb00e59a0abaa4c97b1d65710e4d47fa?urlpath=lab%2Ftree%2Fnotebooks%2Factinia_process_chain.ipynb)

---

## Getting started

The actinia Jupyter notebooks provided here can be easily executed in cloud based
services. We have added launch buttons to Binder and Colab, cloud based services
that can run the Jupyter notebooks. Certainly you can also execute the notebooks
locally on your system.

### Google Colab

In order to run a notebook, simply click on the "launch Google Colab" button.
It will run the notebook for you, for interactive usage.

### Using binder

In order to run a notebook, simply click on the "launch binder" button.
It will start a virtual machine with the notebook for you, for interactive
usage.

### Using the notebooks locally

Clone this repository with `git clone` first. Then locally start the Jupyter notebook
server from the command line in the directory containing the `*.jpynb` files with:
`jupyter notebook`

This will open a new browser tab or window with a list of the contents of the current
working directory. Clicking on one of the `*.jpynb` files will start this particular notebook.

See also the official documentation for [The Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/latest/).
