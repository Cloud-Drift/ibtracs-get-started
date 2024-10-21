[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Cloud-Drift/ibtracs-get-started/HEAD)

# ibtracs-get-started (experimental)
This repository contains a notebooks to get you started with the [IBTrACS dataset](https://www.ncei.noaa.gov/products/international-best-track-archive) using python and the [*xarray* library](https://docs.xarray.dev/en/stable/). 


## Using experimental examples
Make sure you install the dependencies for the notebook and clouddrift:
```bash
conda env create -n ibtracs-get-started -f environment.yaml
conda env update -n ibtracs-get-started --file clouddrift/environment.yaml
```

Utilize the `ibtracs-get-started` environment for the notebooks
