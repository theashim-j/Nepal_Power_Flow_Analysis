# Nepal Transmission Analysis

This repository contains a Jupyter Notebook for analyzing transmission line infrastructure in Nepal. It is intended for the power flow analysis of proposed transmission network of Nepal by 2035.

## Dissertation Context
This analysis is conducted as part of the dissertation titled:

**_"Energy Export Potential of Nepal in BBIN: Challenges in Policy, Diplomacy and Infrastructure"_**  
for the MSc in Energy Systems at the University of Oxford.

## Contents
- `Nepal Transmission Line.ipynb`: Main analysis notebook
- `data/`: Folder to store raw and processed data

## Getting Started
1. Clone the repository
2. Install dependencies (see `Requirements')
3. Run the notebook in JupyterLab or VSCode

## Requirements

To run the notebook and replicate the analysis, you will need the following:

### Python (>=3.8) and packages:
- `pandas` — for data manipulation  
- `numpy` — for numerical operations  
- `geopandas` — for handling geospatial data  
- `matplotlib` — for plotting  
- `shapely` — for geometric operations  
- `fiona` — for file access to spatial formats  
- `pyproj` — for coordinate reference system transformations  
- `jupyterlab` or `notebook` — for interactive notebook environment

You can install all required packages using:

```bash
pip install pandas numpy geopandas matplotlib shapely fiona pyproj jupyterlab
```

Or from a `requirements.txt` (if added):

```bash
pip install -r requirements.txt
```

## License
MIT License
