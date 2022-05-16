[![Binder](https://gesis.mybinder.org/badge_logo.svg)](https://gesis.mybinder.org/v2/gh/fastice/nisarCryoCalValNotebooks.git/HEAD)
# nisarCryoCalValNotebooks
This repository contains the NISAR ice-sheet and glacier ATBD documents and the prototype notebooks for NISAR ice sheet and glacier cal/val activities. 

## [ATBD-Documents](https://github.com/fastice/nisarCryoCalValNotebooks/tree/main/ATBD-Documents)
This directory contains Word and PDF versions of the latest ice-sheet and glacier ATBD documents.

## [calVal-Notebooks](https://github.com/fastice/nisarCryoCalValNotebooks/tree/main/calVal-Notebooks)
This directory contains fully functioning versions of the notebooks can be run by clicking on the binder icon above.

To avoid compatability problems, use the [environment](https://github.com/fastice/nisarCryoCalValNotebooks/blob/main/binder/environment.yml) file in the binder directory for this repository and follow the conda install instructions found [here](https://github.com/fastice/GIMPNotebooks/blob/master/NSIDCLoginNotebook.ipynb), which includes two other github repositories ([nisardev](https://github.com/fastice/nisardev) and [gimpfunc](https://github.com/fastice/gimpfunc)) needed to run these notebooks. 

Run the cells down to the login window, login with valid NASA Earth Data [Credentials](https://urs.earthdata.nasa.gov), the remaining cells can then be run with no further input.  

### [NISAR Slow Movement Validation Notebook: L2-SCI-667](https://github.com/fastice/nisarCryoCalValNotebooks/blob/main/L2-SCI-667-SlowMotion.ipynb)
This notebook is used to validate the requirement for NISAR:

**The NISAR Project shall measure ice sheet (> 90% coverage, including both poles) and glaciers and ice-caps (> 80% coverage) horizontal velocity each cold season to an accuracy better than the sum of 3% of the horizontal velocity magnitude and 1 m/yr (1-sigma), at 100-m resolution in areas of slow deformation (< 50 m/yr).**

### [NISAR Fast Movement Validation Notebook: L2-SCI-668](https://github.com/fastice/nisarCryoCalValNotebooks/blob/main/calVal-Notebooks/L2-SCI-668-FastMotion.ipynb)
This notebook is used to validate the requirement for NISAR:

**The NISAR Project shall measure ice sheet horizontal velocity (90% coverage, including both poles) to an accuracy better than 3% of the horizontal velocity magnitude plus 5 m/yr (1-sigma), at 250-m resolution each cold season in areas of fast deformation (>50 m/yr).**

### [NISAR Ice sheet velocity sampling Validation Notebook: L2-SCI-738](https://github.com/fastice/nisarCryoCalValNotebooks/blob/main/calVal-Notebooks/L2-SCI-738-Sampling.ipynb)
This notebook is used to validate the requirement for NISAR:

To run a demonstration of the notebook on binder click here: [![Binder](https://gesis.mybinder.org/badge_logo.svg)](https://gesis.mybinder.org/v2/gh/fastice/nisarCryoCalValNotebooks.git/HEAD)

## [calVal-CodeExamples](https://github.com/fastice/nisarCryoCalValNotebooks/blob/main/nisarExamples.ipynb)

This directory contains a notebook that demonstrates the functionality of some the tools written to create the validation notebooks. 

## [GPSpoints](https://github.com/fastice/nisarCryoCalValNotebooks/tree/main/GPSpoints)
This directory contains real and potentially synthetic data used to test the cal/val notebook code.
