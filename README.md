# logistic-regression


Problem Statement - Predict the onset of diabetes based on diagnostic measures
Introduction The Pima are a group of Native Americans living in Arizona. A genetic predisposition allowed this group to survive normally to a diet poor of carbohydrates for years. In the recent years, because of a sudden shift from traditional agricultural crops to processed foods, together with a decline in physical activity, made them develop the highest prevalence of type 2 diabetes and for this reason they have been subject of many studies.

Dataset Description The dataset describes the medical records for Pima Indians and whether or not each patient will have an onset of diabetes within few years.

It includes data from 768 women with 8 characteristics:

Fields description follow:

PregnantFreq = Number of times pregnant

PlasmaGlucose = Plasma glucose concentration in 2 hours in an oral glucose tolerance test

DiastolicBP = Diastolic blood pressure (mm Hg)

TricepSkinThickness = Triceps skin fold thickness (mm)

SerumInsulin = 2-Hour serum insulin (mu U/ml)

BMI = Body mass index (weight in kg/(height in m)^2)

DiabetesPedigree = Diabetes pedigree function

Age = Age (years)

Target = Class variable (1: tested positive for diabetes, 0: tested negative for diabetes
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns



from sklearn.model_selection import train_test_split
from sklearn.metrics import confusion_matrix
from sklearn import metrics
