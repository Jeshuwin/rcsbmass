# RCSB PDB Mass Download Notebook

This repository contains a tool that leverages the RCSB PDB Search API to facilitate the bulk downloading of Protein Data Bank (PDB) files and their biological assemblies. With the help of predefined JSON queries, users can easily specify and modify search criteria to retrieve and download a large number of PDB files efficiently.

It simplifies the process of specifying search criteria and handling bulk downloads, making it ideal for researchers and scientists working with protein structures.

## Features


- **Customizable Queries**: Use JSON to define search parameters for precise results.
- **Bulk Downloading**: Automate the retrieval and downloading of numerous PDB files in a few clicks.

## Getting Started

To get started with this notebook, you should have Jupyter installed on your system. If you don't have Jupyter, you can install it via Anaconda or with pip:

```bash
pip install notebook
```

## Getting Started

1. Clone the repository to your local machine.

2. Place your JSON query files in the pdb_json directory.

3. Run the Python script to start the download process based on your search criteria.

### Setting Up Your Search Criteria

To set up your search criteria:

1. Go to the [RCSB PDB website](https://www.rcsb.org) and use the Advanced Search options to define your search criteria.
2. Once you have your results, click on the "Search API" button as shown below:

   ![Search API Button](URL_TO_IMAGE)

3. Copy the JSON query from the RCSB PDB site.
4. Paste the JSON into the corresponding cell in the `rcsb_mass.ipynb` notebook.

