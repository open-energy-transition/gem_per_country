# GEM per Country

This repository hosts the **GEM per Country Power Tracker** web application. The tool allows users to preview and download GeoJSON data for global power plants filtered by country and power plant status. 

## Overview

- **Country Filtering:** Input a country name to display power plant data for that region.
- **Status Filtering:** A dropdown with checkboxes lets you select one or more power plant statuses.
- **Location Accuracy:** A dropdown that allows you to filter by the location accuracy of each power plant returned.
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
