### About

A notebook demonstrating how to subset a remote OPeNDAP dataset by geographical area.

To run in binder, click the button below, then click to open the `opendap_geo_subsetting.ipynb` notebook:

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/catees/opendap_geo_subsetting)

For general information on interacting with Jupyter notebooks, [click here](http://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb).

### For Developers

You must have the `conda` tool available on your path, either from an [Anaconda](https://www.continuum.io/downloads) or [Miniconda](http://conda.pydata.org/miniconda.html) installation.

Run `./develop.sh` to create a development environment and launch Jupyter in your browser (ctrl-c to end the Jupyter session).

Keep `environment.yml` (for deployment conda environments) and `develop.yml` (for local development environments) in sync as necessary. You may need extra packages (e.g. `jupyter`) available for development.

You may want to clean notebooks with _Cell_ > _All Output_ > _Clear_ before committing updates.
