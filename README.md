# MAST30034 Project 1 README.md
- Name: Aryan Shahi
- Student ID: 1170385

## README

**Research Goal:** My research goal is yellow taxi demand analysis based on location, time, and weather

**Timeline:** The timeline for the research area is 2019-2020.

To run the pipeline, please visit the `scripts` directory and run the files in order:
1. `preprocessing.ipynb`: This downloads the raw data into the `data/raw` directory and details all the preprocessing steps and outputs it to the `data/curated` directory.
2. `testing_data.ipynb`: This downloads the raw data into the `data/raw` directory and details all preprocessing steps for the testing data and outputs it to the `data/curated` directory.
3. `analysis.ipynb`: This notebook is used to conduct analysis on the curated data.
4. `model_analysis.ipynb`: This makes the models and is used for analysing and discussing them.

*The weather data is stored in the `data/raw` directory as it is unable to be retrieved via url
**All file downloads are done through notebooks, no scripts are used
