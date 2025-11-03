# replications
Replication of studies creating evals or new training data for improving measurement of empathy in AI models

## Goal
This repository's goal is to reproduce the analyses and outputs from the project hosted at:

https://osf.io/y2hgu/overview

## Virtual environment
A virtual environment is expected at the repository root in the directory `.venv`.
To activate it on Linux (bash):

```bash
# create the venv if it doesn't exist
python -m venv .venv

# activate the venv
source .venv/bin/activate

# install dependencies
pip install -r requirements.txt
```

Notes:
- The example above assumes a system `python` that corresponds to the intended Python version. If you use `python3` or a specific executable, substitute accordingly.
- The `.venv` directory is at the repository root: `./.venv`

## Running the main notebook
The primary notebook for Experiment 1 is `replication_paper/code/E1_Help_Cost_Checking_Model.ipynb`.

Interactive (open in Jupyter Lab / Notebook):


## Data paths
Input data files are under `replication_paper/data/input/`.

Outputs (predictions, results) are written to `replication_paper/data/output/` by the notebook (for example, `e1_help_cost_checking_pred.csv`).

