# Diabetes Readmission Task

In this repository, [Carlos Gomes](https://github.com/CarlosGomes98) and I approach the task of predicting patient readmission.

To replicate, clone this repository and create a conda environment with the necessary packages by running ```conda env create -f env.yml```. Activate this with ```conda activate diab-readmission```.

The first notebook that should be run is feature-engineering, to preform the filtering and cleanup of the data. Inside the data folder is already a cleaned version of the data if you wish to skip this.

The Exploration notebook provides some visualizations of the interaction between different variables that we explored.

Finally, the Model notebook contains our implementation of a predictive model for this task.
