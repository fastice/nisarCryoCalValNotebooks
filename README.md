[![Binder](https://gesis.mybinder.org/badge_logo.svg)](https://gesis.mybinder.org/v2/gh/fastice/nisarCryoCalValNotebooks.git/HEAD)
# nisarCryoCalValNotebooks
NISAR Cal/Val Notebooks
This repository contains prototype notebooks for NISAR ice sheet and glacier cal/val activities. Fully functioning versions of the notebooks can be run by clicking on the binder icon above.

To avoid compatability problems, use the [environment](https://github.com/fastice/nisarCryoCalValNotebooks/blob/main/binder/environment.yml) file in the binder directory for this repository and follow the conda install instructions found [here](https://github.com/fastice/GIMPNotebooks/blob/master/NSIDCLoginNotebook.ipynb), which includes two other github repositories ([nisardev](https://github.com/fastice/nisardev) and [gimpfunc](https://github.com/fastice/gimpfunc)) needed to run these notebooks. 

# NISAR Slow Movement Validation Notebook [L2-SCI-667](https://github.com/fastice/nisarCryoCalValNotebooks/blob/main/L2-SCI-667-SlowMotion.ipynb)

This notebook is used to validate the requirement for NISAR:

**The NISAR Project shall measure ice sheet (> 90% coverage, including both poles) and glaciers and ice-caps (> 80% coverage) horizontal velocity each cold season to an accuracy better than the sum of 3% of the horizontal velocity magnitude and 1 m/yr (1-sigma), at 100-m resolution in areas of slow deformation (< 50 m/yr).**

Run the cells down to the login window, login with valid NASA Earth Data [Credentials](https://urs.earthdata.nasa.gov), the remaining cells can then be run with no further input.  

# NISAR Examples [nisarExamples](https://github.com/fastice/nisarCryoCalValNotebooks/blob/main/nisarExamples.ipynb)

This notebook demonstrates the functionality of some the tools written to create the validation notebooks. 
