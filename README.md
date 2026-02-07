# wikidata

Python scripts for SPARQL queries to visualize wikidata on black artists in Philadelphia

## Overview

This repository contains Jupyter notebooks and Python scripts for querying Wikidata using SPARQL and analyzing results focused on African American artists in Philadelphia.

## Files

- `Querying_and_Visualizing_Wikidata.ipynb` - Main analysis notebook with SPARQL queries and visualizations
- `Query and Visualize Wikidata.ipynb` - Additional analysis variations
- `Wikidata_SPARQL_Queries.ipynb` - Reference guide for SPARQL query syntax
- `querying_and_visualizing_wikidata.py` - Standalone Python script version (executable without Jupyter)
- `Wikidata Query 11_21_2020.csv` - Query results archive (Nov 21, 2020)
- `Wikidata Query 9_9_2021.csv` - Query results archive (Sept 9, 2021)

## Setup

Install required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

### Jupyter Notebook (recommended)
```bash
jupyter notebook Querying_and_Visualizing_Wikidata.ipynb
```

### Python Script (command line)
```bash
python querying_and_visualizing_wikidata.py
```

## Dependencies

- SPARQLWrapper - Query Wikidata SPARQL endpoint
- pandas - Data analysis and manipulation
- plotly - Interactive visualizations
- requests - HTTP library
- numpy - Numerical computing

## Credits

Created by Jay Winkler, Alex Wermer-Colan, Synatra Smith, and Rebecca Bayek

## Related Projects

- Documentation: See artvizphilly.github.io website
- Interactive Analysis: See ../leading_fellows2022 for R/Shiny application

