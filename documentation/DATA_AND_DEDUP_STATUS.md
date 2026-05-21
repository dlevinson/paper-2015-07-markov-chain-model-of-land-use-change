# Data And Deduplication Status

The final paper says the expanded land-use data set has observations for 1958, 1968, 1978, 1984, 1990, 1997, 2000, and 2005. It says pre-1984 data were manually digitized from paper land-use maps at the John R. Borchert Map Library, and selected years from 1984 to 2005 came from the Metropolitan Council parcel-level inventory, converted to raster and harmonized to ten generalized land-use classes.

A readable local GIS source tree was found at:

`/Users/dlev2617/Documents/Data/~Nexus_Data/NSF Career Network Growth/Network Growth CDs/Network Growth CDs/Landuse_GIS`

That local tree appears to contain 1958, 1968, 1978, 1990, and 2000 material, totaling 335 files and 192630838 bytes. A Dropbox mirror was also found at:

`/Users/dlev2617/Sydney Uni Dropbox/David Levinson/Data/Twin Cities Landuse_GIS`

On this machine the Dropbox mirror appears dehydrated/online-only: most files report zero bytes. The visible folder structure has the same years as the local source tree: 1958, 1968, 1978, 1990, and 2000. A targeted Dropbox remote search for `landuse1984`, `landuse1997`, `landuse2005`, and related Twin Cities land-use terms did not find separate 1984, 1997, or 2005 source files. A subset of the same land-use GIS material is already staged in the shared source package:

`/Users/dlev2617/Documents/Code/Agents/github-packages/_shared_sources/twin-cities-historical-landuse-markov/data/markov_gis_public_source_subset/Landuse_GIS`

That staged subset covers 1958, 1968, 1978, and 1990. This package does not duplicate it.

After user review, the large Wei Chen / Paving New Ground Markov source package was moved to `_shared_sources/twin-cities-historical-landuse-markov` and should be treated as the shared historical Markov land-use data source for this paper as well. The dependency is recorded in `documentation/SHARED_DATA_DEPENDENCY.md` and `metadata/SHARED_DATA_DEPENDENCIES.csv`. The intended publication workflow is to point both papers to the shared source package or external data deposit, not to upload a second copy under `paper-2015-07`.

An additional local source was found after user direction at:

`/Users/dlev2617/Documents/Data/~Nexus_Data/Access to Destinations Project/Rania-Iacono Land Use Data`

This source has been copied into:

`data/rania_iacono_grid_land_use_1960_2000`

It contains `All_in1.xlsx`, a 610,988-row grid-level table with `GRIDID` and `TYPE1/2/3` variables for `60`, `70`, `80`, `90`, and `00`, plus the `GRIDsmall` shapefile components. This appears relevant to the Rania Iacono land-use modelling data line and should be retained.

The remaining issue is documentation, not data discovery. The TeMA paper names 1984, 1997, and 2005 as part of the expanded time series, while the visible shared and supplement package files emphasize 1958, 1968, 1978, 1990, 2000, and compact grid fields for 60/70/80/90/00. That should be documented as a provenance/reproducibility caveat around the shared package. It is not a reason to keep hunting through Dropbox or to duplicate the already staged Wei Chen/Paving New Ground Markov data.

Package decision: move `paper-2015-07` to `UPLOADED` and point to `_shared_sources/twin-cities-historical-landuse-markov` plus the local Rania-Iacono supplement. If final transition/regression/forecast scripts later appear, add them as a follow-up code supplement; do not keep this row in `SEARCH` for lack of those scripts.

Last updated: 2026-05-19 11:40:34
