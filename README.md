# Computational-comparison-of-cutting-stock-formulations

This project compares three mathematical models for the one-dimensional Cutting Stock Problem:
* Kantorovich
* Gilmore–Gomory
* Arcflow
The goal is to meet the demand for different piece lengths while using as few stock rolls as possible.
## How to run
1. Open Google Colab.
2. Upload `cutting_stock_colab_fixed.ipynb`.
3. Click Runtime > Run all.
4. Download the two CSV files generated at the end.
The notebook installs PuLP 3.3.0 and uses the CBC solver. 
## Experiment
The three models are tested on the same 10 small cutting stock instances with a 5-second solver time limit per model and instance.
The comparison includes:
- Number of rolls used
- Solver running time
- Number of variables and constraints
- LP relaxation bound
## Results
`detailed_results.csv`: results for each model and instance
`summary_results.csv`: average performance of each model
