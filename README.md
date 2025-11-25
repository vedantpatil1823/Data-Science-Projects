# Data-Science-Projects

A collection of data science projects, experiments, and practical notebooks created to learn and demonstrate workflows in data analysis, machine learning, and visualization. This repository is organized so you can add new practical projects easily — follow the template and guidelines below when you add new work.

## Repository structure

- /project-name/
  - README.md             ← short project overview and instructions (required)
  - data/                 ← raw and/or processed data (see data guidelines)
  - notebooks/            ← Jupyter notebooks (.ipynb) demonstrating experiments
  - src/                  ← scripts, modules, helper functions
  - environment.yml or requirements.txt ← reproducible environment
  - results/              ← outputs: model files, figures, exported tables
- /datasets/              ← (optional) large shared datasets used by multiple projects
- /assets/                ← images and other assets used in repository README(s)

Each project should live in its own directory named with kebab-case (e.g., house-price-prediction).

## How to use this repo

1. Browse the project directories and open the project's README for context.
2. Recreate the environment:
   - With conda (if environment.yml provided):
     ```
     conda env create -f environment.yml
     conda activate <env-name>
     ```
   - With pip (if requirements.txt provided):
     ```
     python -m venv .venv
     source .venv/bin/activate   # macOS / Linux
     .venv\Scripts\activate      # Windows
     pip install -r requirements.txt
     ```
3. Open notebooks:
   ```
   jupyter lab
   ```
   or run scripts in src/ as documented in the project README.

