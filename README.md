# lead-poisoning
Analysis of lead poisoning data as part of the Erdos Institute's data science boot camp.

Authors: Matthew Smylie, Anna Pham, and (formerly) Young Song

## Motivation
There is no safe level of lead in the blood. Childhood exposure to lead remains a vital public health issue, as it has been linked to chronic health problems later in life. However, there are many places in the United States and around the world in which there is a dearth of actual statistics concerning blood lead levels (BLLs) in children. The goal of this project is to examine the data that does exist and to compare it to other social and economic variables. Ideally, we will be able to find good predictors that are better measured, and we may be able to identify regions that are most at risk.

## Contents

### documents
Written deliverables for the project, including the executive summary, presentation slides, and the initial project outline.

### data
The data analyzed in this project, including both the raw data and the cleaned CSV files.

### analysis-complete.ipynb
A Jupyter notebook that runs the full model selection and analysis.

### data-preprocessing.ipynb
A Jupyter notebook that converts the raw data files into useable forms and stores them in data/cleaned.

### data-preprocessing-2.ipynb
A Jupyter notebook that merges the outputs of 'data-preprocessing.ipynb' into 'merged_df', the total data matrix used in the analysis.

### eda.ipynb
Our initial exploratory analysis of the data and first steps toward feature selection.

### old
A directory of old analysis notebooks and experiments marked for removal.
