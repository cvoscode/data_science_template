# This is a cookiecutter teplate for data science with uv

The folder structure is as follows:

    ├── README.md             # Project documentation
    ├── data                  # Data directory
    │   ├── raw               # Raw data (original, immutable)
    │   └── processed         # Processed data (cleaned, ready-to-use)
    │   └── features          # Feature store
    ├── docs                  # place for documentation files
    ├── src                   # Source code for this project
    │   ├── __init__.py       # Initialize package
    │   └── 01_bronce         # Modules for data loading, processing, and analysis
    │   └── 02_silver         # Modules for modelling
    │   └── 03_gold           # Modules for model tuning
    │   └── models            # Model store
    ├── test                  # Tests
    ├── .gitignore            # git config
    └── Makefile              # Make commands for setup, testing, etc.
    └── pyproject.toml        # file to set up environment with uv
    └── ruff.toml             # ruff settings


To set up the project environment and install all required packages, ensure you have UV installed, then run the following commands:

    uvx cookiecutter https://github.com/cvoscode/data_science_template.git

    make install

You should now be good to go.

The following packages will be installed:
- https://auto.gluon.ai/stable/index.html
- https://scikit-learn.org/stable/
- https://imbalanced-learn.org/stable/
- https://pytorch.org/
- https://plotly.com/
- https://pola.rs/
- https://jupyter.org/
- https://dvc.org/
- https://www.deepchecks.com/


If you want to get a full overview over the included packages (and their Versions) in this template run:

    uv pip list

When you need a package not in this template you can run:

    uv add [package_name]

There is no garanty that one of the versions of the packages is fully up to date and secure so please be cautios.
All the packages and software in this template are Open Source and their respective Licenses hold.


