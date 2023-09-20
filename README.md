# crime_hotspot_prediction
This repository contains the code, datasets, and results from a crime hotspot prediction project.

Code: The project's code is shared in the codes.ipynb file. This file contains implementations of selected algorithms (GraphWavenet, STGCN, and LSTM), data preparation (train/test split), hyperparameter tuning, and performance evaluation. Please use caution when running the code, as there may be deprecated packages and libraries. The code has not been updated for a while, but it includes annotations explaining key sections of the script.

Datasets: This repository includes a folder titled Datasets that contains all crime and park event tables. These tables consist of event observations across street segments (columns) with time steps (rows). This is a crucial aspect of the project. Additionally, the folder contains Python pickles that store network information, street segment details, and crime location information. Each file in this folder is required by the script to generate predictions.

Predictions: The folder also contains predictions across all the models (e.g., theft daily, robbery shift). These files have two columns: actual and predicted values, respectively. The structure is 2459 rows by test days. This means that the first 2459 rows represent predictions for each segment on the first day, the next 2459 rows represent predictions for the second day, and so on.

We hope that researchers find this repository useful for their work.
