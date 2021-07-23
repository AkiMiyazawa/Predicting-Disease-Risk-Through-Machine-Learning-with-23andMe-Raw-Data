# Predicting-Disease-Risk-Through-Machine-Learning-with-23andMe-Raw-Data

In this project, my main goal is to predict disease risks through machine learning and to build a program for 23andMe users to input their raw data to receive disease risk predictions. I simulated the dataset used for training the models by using the risk allele frequency (RAF) and beta values for each SNP in the GWAS catalog for each disease. Using XGBoost, I achieved a F1 score of 0.86 for Alzheimer's diease, 0.90 for coronary heart disease, 0.79 for type 1 diabetes, 0.83 for hypertension, and 0.78 for rheumatoid arthritis. I also trained models that are compatible with the raw data 23andMe provides for their users and built a program where a user can input their raw data as well as their age and output their risks for the five diseases based than their genetic data. 

## Usage Instructions 

To run the program that predicts disease risk using 23andMe data, please run `main.py -f your23andmerawdata.txt`. If you don't have your own 23andMe raw data, feel free to use  `example1.txt` or `example2.txt`. 


