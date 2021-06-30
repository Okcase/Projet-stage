# Home

## Main objective

To have data preparation code to handle LPIS type geographic data (agricultural parcels) homogeneously on the European territory.

The objective is to move from multiple and heterogeneous data in specification to more integrated and homogeneous data among themselves.

Indeed today these data are built and disseminated (not all of them) by the various agricultural aid payment European organisms.

Each organism has a it's own data schema, whether this is:

- at the level of the parcel identification attribute

- on the attribute describing the crop of a parcel. The latter often corresponds to a code or a label in a well defined crop nomenclature.

  But this is different depending on the payment organism and is often in the language of it's country.

- on the map projection and the vector data format used.

These different data therefore cannot be easily used jointly. In particular when one wishes to use these data for web displays, statistical studies or for building learning games for AI / Deep-learning algorithms.

More concretely in terms of sub-objective / tasks, this means that we must :

- Identify LPIS data sources and provide a central point to complete and upload this data inventory.
- Document the format of the various original data.
- Allow to translate and simplify the original data (deletion of specific column attributes).
- Allow to reprojete and convert the original data according to specific spatial footprints (sentinel-2 tiling) and geojson format (GIS process).
- Allow to convert data into different code nomenclatures.
- Allow to document and centralize configurations allowing to make nomenclature change.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

