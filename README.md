# Tipping Point Analysis

This repository contains the analysis of survey data asking respondents to classify points on a graph as tipping points or not. The data is publically available and can be found in the `data` folder as either Excel files (the original), as CSV files exported from Excel, or as `.dat` files that have been preprocessed (for details see `01_preprocessing.ipynb`) and turned into dataframe type objects that are compatible with both Julia DataFrames and Python pandas DataFrames (and I also imagine R, although that hasn't been tested).

# To reproduce

The analysis was partially done in Julia (`01_preprocessing.ipynb`, `02_descriptive_logistic.ipynb`, `tables.ipynb`) and partially done in Python (`03_random_forests.ipynb`) due to the power of scikitlearn. A Julia project environment has been set up with the necessary packages. Because of how `IJulia` works, there should be no additional effort required, you can simply run and execute the Julia notebooks directly. I still need to set up a Conda environment for the required Python packages.
