![](https://img.shields.io/badge/language-python-yellow.svg)
![](https://img.shields.io/badge/license-apache_2.0-000000.svg)
![](https://progress-bar.dev/100)

# Titanic survivability prediction

This is a [kaggle competition](https://www.kaggle.com/competitions/titanic) project. The goal is to find the best model
for predicting wether titanic passenger survived the catastrophe. For this
task I have cleaned and preprocessed the data and then used **Logistic Regression Classifier**
and **Random Forest Classifier** to model and predict survivability.

## Inspect online

To view this project online you can either do it here on github by clicking
on `titanic_survival_prediction.ipynb`, using *NBViewer* or on my [portfolio website](https://f1lem0n.github.io/)

## Run my project

To run this project you will need an environment. Do not worry as I have created a `.yml` file
to instantly create a *conda* environment. All you need to do is run the following script
in your terminal/PowerShell. Obviously you need to install *conda* prior to environment creation.

```{bash}
git clone https://www.github.com/f1lem0n/titanic.git
cd titanic
conda env create -f conda-env.yml -y
conda activate titanic
```
