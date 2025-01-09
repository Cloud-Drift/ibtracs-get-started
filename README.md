[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Cloud-Drift/ibtracs-get-started/HEAD)

# ibtracs-get-started (experimental)
This repository contains a notebook to get you started with the [IBTrACS dataset](https://www.ncei.noaa.gov/products/international-best-track-archive) using the [*clouddrift* library](https://clouddrift.org/).


## Using experimental examples
Since the [dataset adapter PR](https://github.com/Cloud-Drift/clouddrift/pull/493) isn't merged in and released as part of a `clouddrift` release, a bit of extra setup is required to run the example notebooks.

1. Initialize the clouddrift library submodule.

```bash
git submodule init
git submodule update
```

2. Setup the environment which we'll utilize to run the notebooks.

```bash
conda env create -n ibtracs-get-started -f environment.yml
conda env update -n ibtracs-get-started --file dependencies/clouddrift/environment.yml
```

3. Utilize the `ibtracs-get-started` environment.

```bash
conda activate ibtracs-get-started
```
