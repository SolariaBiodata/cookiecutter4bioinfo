# {{ cookiecutter.project_title }}

{{ cookiecutter.description }}

By: {{ cookiecutter.author }}

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

## Getting started

**Before you start**

- Get sure you have `python` with a version {{ cookiecutter.python_version }}, if you want to start from fresh take a look at [this resource](https://wiki.python.org/moin/BeginnersGuide/Download).


Make sure have installed:
 - `conda`
 - `cookiecutter`

Init your project by:

```bash
conda activate {{ cookiecutter.project_slug }}
```


## Contact info

[{{ cookiecutter.author }}](mailto:{{ cookiecutter.git_email }})