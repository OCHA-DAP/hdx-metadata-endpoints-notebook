# HDX Metadata API Endpoints Quickstart

This repository contains a Jupyter Notebook using Python that demonstrates how to interact with the [HDX Metadata API Endpoints](https://docs.humdata.org/build/hdx-apis/metadata-endpoints). It is a hands-on guide for discovering datasets, exploring metadata, downloading files, and querying tabular data on HDX. You can use it as inspiration for incorporating HDX data into your own workflows.

For more information, please refer to the HDX documentation or reach out using the contact details below.

## Contents
- **hdx_metadata_endpoints.ipynb** This Jupyter notebook walks through how to:
  - Search the HDX catalogue by topic and country
  - Use facets for platform analytics (datasets by country, organisation)
  - Retrieve full metadata for a specific dataset with `package_show`
  - Build an automated file download pipeline
  - Run an end-to-end workflow combining metadata endpoints with Tabular Data Endpoints

## Requirements
- Python 3.8+
- Jupyter Notebook
- Python libraries:
  - `pandas`
  - `requests`
  - `matplotlib`
  - `geopandas`
  - `contextily`
- HDX API Token (see information [here](https://docs.humdata.org/build/overview/hdx-core-concepts))

Install dependencies with:

```
pip install pandas requests matplotlib geopandas contextily jupyter
```

## How to use

1. Clone this repository:
```
git clone https://github.com/OCHA-DAP/hdx-metadata-endpoints-notebook.git
cd hdx-metadata-endpoints-notebook
```

2. Launch Jupyter:
```
jupyter notebook
```

3. Open **hdx_metadata_endpoints.ipynb** and follow the instructions cell by cell.

## Questions?
Contributions, improvements, or additional dataset examples are always welcome! Please reach out to HDX by emailing [hdx@un.org](mailto:hdx@un.org).
