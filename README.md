# SPA-fNIRS Test-Retest Reliability
This repository contains the code for conducting GLM analyses on fNIRS data, as presented in the manuscript: *Intra-subject test-retest reliability for auditory-evoked fNIRS responses: Effects of systemic physiology correction*. The goal of this project is to evaluate how correcting for systemic physiological signals affects reliability in single-subject fNIRS data.

## Requirements:
This script was executed with **Python 3.11** in **Jupyter Notebook**. The necessary libraries and packages are imported within the script, including MNE and MNE-NIRS.

## The Script:
To run the analysis:
1. Open the `glm_analysis_script_SPA-fNIRS.ipynb` notebook.
2. Execute the cells sequentially, ensuring all cells are run from top to bottom.

## Data:
The script expects fNIRS data in formats such as `.snirf`. Make sure your data is correctly preprocessed and formatted as described in the manuscript before running the notebook.

## Output:
The script stores the GLM results as CSV files. These are pre-formatted for external plotting, as demonstrated in **Figure 4** of the manuscript. Review the results before plotting to ensure they align with your analysis requirements and visualization preferences.

## General Notes:
- This Python script is written for **Jupyter Notebook** and uses **MNE-NIRS** tools. More information on MNE-NIRS can be found [here](https://mne.tools/mne-nirs/stable/index.html).
- The script will:
    - Import the required libraries and packages.
    - Define functions to implement five correction models (investigated in the manuscript, but flexible for modification).
    - Run GLM analyses for each model.
    - Format the results for external plotting

## Citation:
If you use this code in your research, please cite the manuscript: *Intra-subject test-retest reliability for auditory-evoked fNIRS responses: Effects of systemic physiology correction*.
