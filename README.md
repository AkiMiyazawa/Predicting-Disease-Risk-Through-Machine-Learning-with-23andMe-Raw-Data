# Predicting-Disease-Risk-Through-Machine-Learning-with-23andMe-Raw-Data

In this project, my main goal is to predict disease risks through machine learning and to build a program for 23andMe users to input their raw data to receive disease risk predictions. I simulated the dataset used for training the models by using the risk allele frequency (RAF) and beta values for each SNP in the GWAS catalog for each disease. Using XGBoost, I achieved a F1 score of 0.86 for Alzheimer's diease, 0.90 for coronary heart disease, 0.79 for type 1 diabetes, 0.83 for hypertension, and 0.78 for rheumatoid arthritis. I also trained models that are compatible with the raw data 23andMe provides for their users and built a program where a user can input their raw data as well as their age and output their risks for the five diseases based than their genetic data. 

## Usage Instructions 

To run the program that predicts disease risk using 23andMe data, please run `main.py -f your23andmerawdata.txt`. If you don't have your own 23andMe raw data, feel free to use  `example1.txt` or `example2.txt`. See requirements.txt for the list of python packages required to run the project. 

## Description of Contents

The project consists of these portions:
```
PROJECT
├── 23andme
│   ├── data
│   └── 23andme experiment.ipynb
│   └──alzheimer
│   └──arthritis
│   └──diabetes
│   └──heart
│   └──hypertension
├── models
│   ├── alzheimer
│   └──arthritis
│   └──diabetes
│   └──heart
│   └──hypertension
├── README.md
├── requirements.txt
└── main.py
└── example1.txt
└── example2.txt
```

### `root`

* `main.py`: Python script to run the program that takes 23andme raw user data as input.

* `example1.txt`: Sample 23andme user raw data

* `example2.txt`: Sample 23andme user raw data

### `23andme`
This directory contains notebooks and data used for creating models that can be used for 23andme raw user data. 

* `data`: Folder that contains the dataset from GWAS catalog as well as processed dataset.

* `23andme experiment.ipynb`: The notebook experiment to figure out how to create dataset used for training the models that can be compatible with 23andme data.

* `alzheimer`: Contains notebook for processing data and training model as well as the saved models.

* `arthritis`: Contains notebook for processing data and training model as well as the saved models.

* `diabetes`: Contains notebook for processing data and training model as well as the saved models.

* `heart`: Contains notebook for processing data and training model as well as the saved models.

* `hypertension`: Contains notebook for processing data and training model as well as the saved models.

### `models`
This directory contains notebooks and data used to train models that perform disease risk prediction (not compatible with 23andme raw user data. 
* `alzheimer`: Contains notebook for processing data and training model as well as the saved models.

* `arthritis`: Contains notebook for processing data and training model as well as the saved models.

* `diabetes`: Contains notebook for processing data and training model as well as the saved models.

* `heart`: Contains notebook for processing data and training model as well as the saved models.

* `hypertension`: Contains notebook for processing data and training model as well as the saved models.


