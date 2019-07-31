
## GRID_LLC90

The included files define the global grid known as `LLC90` which was introduced as part of the `ECCOv4` ocean modeling framework [Forget et al., 2015](http://www.geosci-model-dev.net/8/3071/2015/), `doi:10.5194/gmd-8-3071-2015`.

- the `tile00?.mitgrid` files are the native grid files (model input; 2D split in 5 subdomains).
- `*.data` and `*.meta` files are the corresponding model output after adding vertical discretization and land mask (3D; global domain).
- `v4_basin.bin` is a map of ocean basin indices (useful to analyze model output).

