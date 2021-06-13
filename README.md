# Robust management of biodiversity data for conservation: The Trillium pusillum complex
Supplimental information documenting various python scripts used in the cleaning, organization, and analysis of Trillium pusillum complex occurrence records.

- "pairwise_TCL_analysis.ipynb" documents the quantification of shared, and exclusive occurrences among TCL pairs.
    - The "pairwise_output" subfolder contains the primary output tables of the pairwise analysis.
- "pairwise_TCL_mapping.ipynb" documents the vizualization of shared, and exclusive occurrences among TCL pairs.
    - The "pairwise_output/mapping" subfolder contains the figures this script generates.
    - The geodatabase generated from this script has been omitted from the repository due to protected statuses.
    - The "ref" subfolder contains a shapefile of the US states obtained from the [US Census bureau](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html)

- "wrangle_occurrences.ipynb" documents the data organization, and cleaning of Trillium pusillum complex occurrence records derived from multiple sources.
    - The "ref" subfolder contains geospatial reference files useful for geocoding occurrences to county centroids.

__Note:__ The input files referenced in these scripts have been omitted from the repository due to protected statuses.
