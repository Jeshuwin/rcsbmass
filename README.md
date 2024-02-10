# RCSB PDB Mass Download Notebook

This repository contains a tool that leverages the RCSB PDB Search API to facilitate the bulk downloading of Protein Data Bank (PDB) files and their biological assemblies. With the help of predefined JSON queries, users can easily specify and modify search criteria to retrieve and download a large number of PDB files efficiently.

It simplifies the process of specifying search criteria and handling bulk downloads, making it ideal for working with large sets of protein structures.

## Features

- **Customizable Queries**: Use JSON to define search parameters for precise results.
- **Bulk Downloading**: Automate the retrieval and downloading of numerous PDB files in a few clicks.
- **Efficiency**: Bypass the website's limitations on batch sizes for an enhanced downloading process.
- **Stability**: Avoid website crashes and timeouts with robust API calls.
- **Speed**: Quickly adjust search parameters and execute downloads faster than manual processes.

## Getting Started

To get started with this notebook, you should have Jupyter installed on your system. If you don't have Jupyter, you can install it via Anaconda or with pip:

```bash
pip install notebook
```

### Setting Up Your Search Criteria

To set up your search criteria:

1. Go to the [RCSB PDB website](https://www.rcsb.org) and use the Advanced Search options to define your search criteria.
2. Once you have your results, click on the "Search API" button as shown below:

   ![Search API Button](https://i.ibb.co/M9pNbhH/pdbs.png)

3. Copy the JSON query from the RCSB PDB site.
   
   ![JSON Query Button](https://i.ibb.co/ZKpKST8/rgross.png)

4. Paste into a new text file and save as a new .json in the pdb_json directory.

## Downloading PDB Files
1. Open the `rcsb_mass.ipynb` notebook in Jupyter.
2. Modify the cell with the path to your JSON file
```python
# Define the path to your JSON file
json_file_path = 'pdb_json/your_query_file.json'  # Adjust the filename as needed
```
3. Run the remaining cells to start the download process based on your search criteria.
   ![downloaded](https://i.ibb.co/FVcTjtQ/fcell.png)
