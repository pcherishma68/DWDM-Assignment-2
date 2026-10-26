# Experiment 1: Data Cleaning Using Orange

## Aim
To clean missing values in the Titanic dataset using Orange Data Mining.

## Dataset
- File: `titanic.csv`
- Total instances: 891
- Features: 9

## Workflow
`File → Impute → Data Table`

## Procedure
1. Imported the Titanic dataset using the File widget.
2. Connected the dataset to the Impute widget.
3. Selected the Average/Most frequent method.
4. Connected Impute to Data Table to inspect the cleaned data.

## Output
Missing numerical values such as Age were replaced using the average value. Categorical missing values were handled using the most frequent value.

## Result
Data cleaning was performed successfully using Orange Data Mining.
