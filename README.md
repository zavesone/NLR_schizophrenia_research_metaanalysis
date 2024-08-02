# Meta-Analysis of Neutrophil-to-Lymphocyte Ratio in Schizophrenia

This repository contains the Python code used to conduct a meta-analysis on the Neutrophil-to-Lymphocyte Ratio (NLR) in patients with various types of schizophrenia compared to healthy controls.

## Project Overview

This meta-analysis investigates the differences in NLR between different schizophrenia subgroups and healthy individuals. The analysis includes data from multiple studies, considering four specific subtypes of schizophrenia and a combined group.

## Contents

- `nlr_meta_analysis.py`: Python script containing the analysis code and forest plot generation
- `forest_plot.png`: Output forest plot visualizing the results

## Schizophrenia Subgroups Analyzed

1. Schizophrenia Unspecified (n = 9148)
2. First Episode Schizophrenia (n = 648)
3. Schizophrenia Remission (n = 3019)
4. Schizophrenia Without Remission (n = 1256)
5. Combined Schizophrenia Group (n = 14071)

## Methods

- Calculation of mean differences in NLR between each schizophrenia subgroup and the control group
- Computation of standard errors and 95% confidence intervals
- Forest plot visualization of mean differences and confidence intervals
- Sample size consideration for each subgroup

## Key Visualizations

The main output is a forest plot (`forest_plot.png`) that displays:
- Mean NLR differences between each schizophrenia subgroup and the control group
- 95% confidence intervals for each mean difference
- Sample sizes for each subgroup

## Requirements

- Python 3.x
- Libraries: numpy, matplotlib
- google collab/jupyternotebook

## Usage

Use the google collab to run the NRL_schizo_meta_analysis.ipynb notebook.

## Results Interpretation

The forest plot shows the mean differences in NLR for each schizophrenia subgroup compared to the control group. Positive values indicate higher NLR in the schizophrenia group. The plot allows for visual comparison of the effect sizes across different schizophrenia subtypes.The paper link will be added soon.

## Contributors

Fedor Kostin

## Contact

For any queries regarding this project, please open an issue in this repository or contact [fedor3016@gmail.com].
