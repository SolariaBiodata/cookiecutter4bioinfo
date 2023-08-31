# Bioinformatics simple template


This repository provides a template that incorporates best practices to create a maintainable and reproducible bioinformatics project.

## Tools used in this project
 - [conda](#) for environment management
 - [git](#) for Code Version Control
 
 ## Project Structure

```bash
.
├── data            
│   ├── processed                   # data after processing
│   ├── raw                         # raw data
│   └── results                     # data results
├── docs                            # documentation for your project
├── environment.yaml                # conda environment file
├── notebooks                       # store notebooks
├── README.md                       # describe your project
├── reports                         # store reports
└── src                             # store source code
    ├── __init__.py                 # make src a Python module 
    ├── helpers                     # helpers functions folder
    └── main.py                     # main analysis
```

## How to use this project

Install Cookiecutter using an environment:
```bash
pip install cookiecutter
```

```bash
conda install cookiecutter
```

Create a project based on the template:
```bash
cookiecutter https://github.com/SolariaBiodata/cookiecutter4bioinfo --checkout main
```

Enjoy!

## Contact info

- [Solaria Biodata](https://www.solariabiodata.com.mx)
- [Send us an email!](mailto:admin-project@solariabiodta.com.mx)
