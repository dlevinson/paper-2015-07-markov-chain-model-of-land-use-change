# A Markov Chain Model of Land Use Change

## Bibliographic Information

- Row ID: `paper-2015-07`
- Citation: Iacono, Michael; Levinson, David; El-Geneidy, Ahmed; Wasfi, Rania. (2015). A Markov Chain Model of Land Use Change. TeMA - Journal of Land Use, Mobility and Environment, 8(3), 263-276. https://doi.org/10.6092/1970-9870/2985

## Package Status

Ready for public upload review as a shared-data package pointer plus paper-specific supplement. The final paper is included, and the Rania-Iacono grid source has been copied into `data/rania_iacono_grid_land_use_1960_2000`. The main historical Markov/Twin Cities source-map data live once in `_shared_sources/twin-cities-historical-landuse-markov`, rather than being duplicated here or owned by `paper-2005-04`.

Current pipeline state: `READY-TO-UPLOAD/PUBLIC`.

## Contents

- `paper/A-Markov-Chain-Model-of-Land-Use-Change.pdf`: final published TeMA PDF used for audit validation.
- `data/rania_iacono_grid_land_use_1960_2000/All_in1.xlsx`: grid-level land-use type table with `GRIDID` and `TYPE1/2/3` variables for `60`, `70`, `80`, `90`, and `00`.
- `data/rania_iacono_grid_land_use_1960_2000/Grid/`: `GRIDsmall` shapefile components for the grid geometry associated with `All_in1.xlsx`.
- `documentation/DATA_AND_DEDUP_STATUS.md`: data/source status and deduplication decision.
- `documentation/SHARED_DATA_DEPENDENCY.md`: pointer to the shared Markov land-use and Data Curation source-map package.
- `metadata/LANDUSE_GIS_SOURCE_PROFILE.csv`: profile of found and missing land-use GIS source candidates.
- `metadata/SOURCE_FILE_DECISIONS.csv`: source-by-source inclusion and exclusion decisions.
- `metadata/RANIA_IACONO_GRID_SOURCE_PROFILE.csv`: profile and checksums for the newly staged Rania-Iacono grid source.
- `metadata/SHARED_DATA_DEPENDENCIES.csv`: machine-readable dependency on `_shared_sources/twin-cities-historical-landuse-markov`.

## Main Finding

The paper states a land-use time series for 1958, 1968, 1978, 1984, 1990, 1997, 2000, and 2005. The canonical shared source for the historical Markov land-use material is `_shared_sources/twin-cities-historical-landuse-markov`, which includes `Markov_database`, `Landuse_GIS`, the `Data Curation` source-map/network-map preservation copy, and public UMN deposit links for the historical source maps/networks. The Rania-Iacono folder adds a compact grid-level source table and grid geometry covering `60`, `70`, `80`, `90`, and `00`.

Final analysis scripts are not packaged. That is a documented reproducibility caveat, not a reason to keep this row in `SEARCH`, because the relevant data sources are already staged or linked through the shared package.

Last updated: 2026-05-19 11:40:34

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-20 14:46:37 AEST

- Pipeline: `READY-TO-UPLOAD/PUBLIC`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
