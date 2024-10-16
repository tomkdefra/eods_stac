# STAC to GeoParquet Conversion in Databricks

This repository contains code for converting SpatioTemporal Asset Catalog (STAC) data to GeoParquet format, designed to run within a Databricks environment. The conversion process uses the [stac-geoparquet](https://stac-utils.github.io/stac-geoparquet/) library to transform STAC items into a more efficient, columnar storage format for geospatial data (GeoParquet), which integrates well with Databricks and Apache Spark workflows.

## Table of Contents

- [Overview](#overview)
- [Setup](#setup)
  - [Clone the Repository](#clone-the-repository)
- [References](#references)

## Overview

The main focus of this project is to convert STAC data into the GeoParquet format to test a more efficient method for cataloging and querying EODS data on DASH. 

Key Features:
- Create STAC items and catalogue from EODS .tif files using `pystac` and stac extensions.
- Convert STAC items to GeoParquet using `stac-geoparquet`.

## Setup

### Clone the Repository

To use this repository within Databricks, you can directly clone it into your Databricks workspace as a Git folder. Follow the steps in the [Databricks documentation](https://docs.databricks.com/en/repos/git-operations-with-repos.html#clone-a-repo-connected-to-a-remote-git-repository) 

## References

- [Create a STAC Item that Implements the Extensions Using PySTAC](https://stacspec.org/en/tutorials/3-create-stac-item-with-extension/)
- [Converting to Parquet](https://stac-utils.github.io/stac-geoparquet/latest/examples/naip/)