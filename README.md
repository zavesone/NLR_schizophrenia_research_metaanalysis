# Statistical Summary of Neutrophil-to-Lymphocyte Ratio in Schizophrenia
![mygif](https://s12.gifyu.com/images/SDs0v.gif)

This repository contains the Python code used to conduct a statistical summary on the Neutrophil-to-Lymphocyte Ratio (NLR) in patients with various types of schizophrenia compared to healthy controls.

## Project Evolution
Initially aimed at meta-analyzing NLR as a risk marker for metabolic disorders in schizophrenia, the project scope was adjusted due to limited available studies. The current analysis focuses on summarizing NLR differences between schizophrenia patients and healthy controls.

## Project Overview
This analysis investigates the differences in NLR between different schizophrenia subgroups and healthy individuals. It includes data from multiple studies, considering four specific subtypes of schizophrenia and a combined group.

## Contents
- `NRL_schizo_meta_analysis.ipynb`: Jupyter notebook containing the analysis code and forest plot generation
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
- Google Colab or Jupyter Notebook

## Usage
Use Google Colab to run the NRL_schizo_meta_analysis.ipynb notebook.

## Results Interpretation
The forest plot shows the mean differences in NLR for each schizophrenia subgroup compared to the control group. Positive values indicate higher NLR in the schizophrenia group. The plot allows for visual comparison of the effect sizes across different schizophrenia subtypes. While not directly addressing NLR as a risk marker for metabolic disorders, these results provide insights into NLR differences in schizophrenia that may inform future research.

## Limitations
- The analysis does not specifically examine NLR as a risk marker for metabolic disorders in schizophrenia.
- Findings are based on a statistical summary rather than a full meta-analysis.

## Future Directions
Further research is needed to explore the relationship between NLR, schizophrenia, and metabolic disorders. Studies specifically examining NLR as a risk marker for metabolic disorders in schizophrenia patients are recommended.

## Contributors
N.V. Zakharova
The Institute of Personalized Psychiatry and Neurology, St Petersburg V. M. Bekhterev National Medical Research Center for Psychiatry and Neurology, Leading Researcher

R.F. Nasyrova
The Institute of Personalized Psychiatry and Neurology, St Petersburg V. M. Bekhterev National Medical Research Center for Psychiatry and Neurology, Leading Researcher

M.N. Rumyantseva
St. Nicholas Psychiatric Hospital, St Petersburg

A.I. Rakhmatullin
North-Western State Medical University named after I.I. Mechnikov, St. Petersburg

K.I. Sizykh
Almazov National Medical Research Centre, St. Petersburg

F.N. Kostin
Independent Researcher, Provided code and conducted statistical analyses

## Contact
For any queries regarding this project, please open an issue in this repository or contact [fedor3016@gmail.com].

## Commitment to Open Science
This project adheres to the principles of open science, promoting transparency and reproducibility in research. By sharing this code, we aim to contribute to the collective advancement of knowledge in the field of schizophrenia research and analytical methods.

![mygif](https://s12.gifyu.com/images/SDxHt.gif)

*"In the spirit of scientific collaboration, we believe that open access to methodologies accelerates progress and fosters innovation."*

By making this code publicly available, we invite peers to review, validate, and build upon our work, ultimately strengthening the reliability of scientific findings in our field.
