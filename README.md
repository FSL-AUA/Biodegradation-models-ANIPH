ANIPH Machine Learning Models

This repository contains the machine learning workflow developed in the ANIPH project for predicting biodegradation and weight loss percentage of PHBV polymers. Models are developed for short-chain-length PHAs (sclPHAs).

Each subfolder corresponds to a specific property/material combination and contains:

Original dataset (*PHAs.xlsx)

Preprocessing notebook (*_data_preprocessing_LM.ipynb)

Cleaned dataset (*_LM.csv) Dataset obtained after preprocessing (cleaning, filtering, unit harmonization, removing invalid samples).

Final training and deployment on Jaqpot notebook (*_regression_LM.ipynb)

The deployed models on Jaqpot were trained and optimized using Random Forest and tailored to the available experimental data.
