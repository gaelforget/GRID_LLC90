
## GRID_LLC90

[![DOI](https://zenodo.org/badge/199910709.svg)](https://zenodo.org/badge/latestdoi/199910709)

The included files define the global grid known as `LLC90` which was introduced as part of the [MITgcm](http://mitgcm.org) / [ECCOv4](https://www.ecco-group.org) ocean modeling framework [Forget et al., 2015](http://www.geosci-model-dev.net/8/3071/2015/), [doi:10.5194/gmd-8-3071-2015](https://doi.org/10.5194/gmd-8-3071-2015).

- the `tile00?.mitgrid` files are the native grid files (model input; 2D split in 5 subdomains).
- `*.data` and `*.meta` files are the corresponding model output after adding vertical discretization and land mask (3D; global domain).

In addition:

- `v4_basin.bin` is a map of ocean basin indices (useful to analyze model output).
- `SSH.bin`, `TrspX.bin`, `TrspY.bin`, `TauX.bin`, and `TauX.bin` are time-mean 2D climatologies from `ECCOv4 release 2` for sea surface height (m), wind stress (N/m2), and top-to-bottom seawater transport (m3/s).

