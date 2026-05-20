# Shared Data Dependency

This paper should share the historical Markov land-use data now staged once under `_shared_sources`:

`/Users/dlev2617/Documents/Code/Agents/github-packages/_shared_sources/twin-cities-historical-landuse-markov/data/markov_gis_public_source_subset`

That shared package includes the `Markov_database` outputs and `Landuse_GIS` source subset used for the earlier Paving New Ground work by David M. Levinson and Wei Chen. The staged subset is about 1.1 GB and has 540 files. It includes `Markov_database` result folders for `58`, `68`, `78`, and `90`, plus `Landuse_GIS` folders for `1958`, `1968`, `1978`, and `1990`.

The same shared source package also includes the Data Curation source-map preservation copy:

`/Users/dlev2617/Documents/Code/Agents/github-packages/_shared_sources/twin-cities-historical-landuse-markov/data/data_curation_twin_cities_source_maps`

That folder preserves `Twin Cities Land Use Maps` and `Twin Cities Network Maps` from `/Users/dlev2617/Documents/Projects-Completed/Data Curation`, excluding `.DS_Store` system files. The package also includes `documentation/UMN_Digital_Conservancy_Deposit_Agreement_Historic_Twin_Cities_Maps.pdf`, the UMN Digital Conservancy deposit agreement for "Historic Twin Cities Land Use Maps and Street Networks".

Because the principal 1958, 1968, and 1978 land-use maps and the 1920-1995 highway network are already deposited in UDC/DRUM, `paper-2015-07` should point to `_shared_sources/twin-cities-historical-landuse-markov/metadata/PUBLIC_DEPOSIT_LINKS.csv` rather than duplicate those deposited public assets.

For this 2015 TeMA paper, the shared-data relationship should be documented rather than duplicated. The `paper-2015-07` package should point to the shared source package and its public deposit-link metadata.

The local `paper-2015-07` package additionally contains:

`data/rania_iacono_grid_land_use_1960_2000`

That folder contains `All_in1.xlsx` and the `GRIDsmall` shapefile components from the Rania-Iacono land-use data folder. It is a compact grid-level supplement covering `60`, `70`, `80`, `90`, and `00` fields.

Remaining caution: the 2015 paper names 1984, 1997, and 2005 as part of the expanded land-use time series. Those years are not visibly represented as standalone folders in the currently staged `markov_gis_public_source_subset`, the local Rania-Iacono supplement, or the Dropbox `Twin Cities Landuse_GIS` mirror. The Data Curation source-map copy and public deposit links improve preservation context for the underlying historical maps and networks, but they do not by themselves prove the final 2015 modelling scripts. Treat this as a documented reproducibility caveat, not as a `SEARCH` blocker.

Last updated: 2026-05-19 11:40:34
