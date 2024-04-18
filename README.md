# Stock-Filing-Analysis

This repository contains the files and assignments for the analysis of SEC Form 4 Filings.

## Repository Structure

- `PFE/`: Directory containing Python scripts for data preprocessing and analysis on PFE Form 4 filings.
- `art3B.ipynb`: Jupyter notebook for Part 3B of the assignment with model building and prediction.
- `Assignment.pdf`: The assignment brief detailing the requirements for each part of the project.
- `CheckFormat.ipynb`: Jupyter notebook used to check the format of the data.
- `Part1B.csv`: CSV file output by the `CreateDataFrame` function from Part 1 of the assignment.
- `Part3A.csv`: CSV file containing the predictions for the test dataset from Part 3A of the assignment.
- `Part1.ipynb`: Jupyter notebook for Part 1 of the assignment, including the `CreateDataFrame` function.
- `Part2.ipynb`: Jupyter notebook for Part 2 of the assignment, which involves data analysis.
- `Part3B.ipynb`: Jupyter notebook for Part 3B of the assignment, which includes the code and prediction of `M`.
- `PFE.csv`: A CSV file containing cleaned data from PFE Form 4 filings.
- `PFESharePrice...`: The file name is truncated, likely contains historical share price data for PFE.
- `test029.csv`: Test dataset provided for Part 3 of the assignment without `DSHARES`.
- `train029.csv`: Training dataset provided for Part 3 of the assignment with `DSHARES`.

## Instructions

Each notebook and CSV file corresponds to a specific part of the assignment. The details of each part can be found in `Assignment.pdf`. Make sure to follow the order of the parts when reviewing the notebooks and datasets.

### Part 1

- `Part1.ipynb`: Contains the code to generate a DataFrame from raw Form 4 filings.
- `Part1B.csv`: The generated CSV file from the `CreateDataFrame` function in `Part1.ipynb`.

### Part 2

- `Part2.ipynb`: Involves analyzing the DataFrame from Part 1 and possibly additional data manipulation and analysis.

### Part 3

- `Part3A.csv`: The predictions file to be submitted for Part 3A.
- `Part3B.ipynb`: Contains the analysis and prediction model for Part 3 of the assignment.

## Data Description

Form 4 Filings data provided by the SEC are used in this project to understand and analyze executive employee stock transactions in publicly traded companies. The analysis is performed in multiple parts, each requiring data manipulation, analysis, and model predictions.
