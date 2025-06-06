# GEM per Country

This repository hosts the **GEM per Country Power Tracker** web application. The tool allows users to preview and download GeoJSON data for global power plants filtered by country and power plant status. The tool also allows exporting a list of steel and iron plants which identifies large loads on the grid as curated by GEM, the same filters apply.

## Overview

- **Dataset Picker:** Choose one of two datasets, the Power plants dataset or the Iron and Steel dataset that shows locations of large loads connected to the grid.
- **Country Filtering:** Input a country name to display power plant data for that region
- **Pagination:** The data preview is paginated to show 2000 rows per page.
- **GeoJSON Download:** Export your filtered data as a GeoJSON file.

## Data Source

The power plant data is sourced from [Global Energy Monitor](https://globalenergymonitor.org/) and is made available under the [Creative Commons Attribution 4.0 License](https://globalenergymonitor.org/creative-commons-public-license/).

## Getting Started

### Prerequisites

No special dependencies are required for running this application locally. 

### Running Locally

1. **Clone the Repository:**

   ```bash
   git clone git@github.com:open-energy-transition/gem_per_country.git
