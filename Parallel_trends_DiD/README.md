# Parallel Trends DiD Analysis

This project demonstrates the Difference-in-Differences (DiD) approach for causal inference, including simulation of data, regression analysis, and diagnostic tests for the parallel trends assumption.

## Environment Specification

The environment is specified in `environment.yml` and includes the following main packages:

- Python 3.x
- pandas
- numpy
- matplotlib
- statsmodels

To create the environment, run:

```sh
conda env create -f environment.yml
conda activate <your_env_name>
```

Replace `<your_env_name>` with the name specified in `environment.yml`.

## Usage

Open the `DiD_parallel_trends.ipynb` notebook and run the cells in order. The notebook will:
- Simulate data for two cities with and without parallel trends
- Fit OLS regression models for DiD analysis
- Visualize results
- Perform pre-trend and placebo tests

## File Structure
- `DiD_parallel_trends.ipynb`: Main analysis notebook
- `environment.yml`: Conda environment specification

## Requirements
- Anaconda or Miniconda
- Jupyter Notebook or VS Code with Jupyter extension

