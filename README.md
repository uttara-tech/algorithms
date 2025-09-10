# README #

## Overview ##


### 1.	Predict LoS (Length of Stay) of patients in a hospital ###
**Objective:** Prediction using Keras Model

**Frameworks and Libraries:** TensorFlow, Keras, Scikit-learn, Numpy, Pandas, Matplotlib, Seaborn

**Overview:**

a. Pre-processing data by:
    
    i) data cleaning, drop redundant columns and fill in missing values in cells

    ii) splitting data into numerical and categorical groups, 
    
    iii) train and test dataset

b. Pre-process categorical features using:
    
    i) One Hot Encoding

    ii) Label Encoding

    iii) Tokenizer

    iv) Pre-process numeric data using convolution Neural Network for extracting features.

    v) Concatenate all inputs using a dictionary.

    vi) Pass this concatenated input to Keras Model.

    vii) Compile and Build the model


### 2.	Wine data analysis ###
**Objective**: Hyperparameter Tuning and Pipelining using XGBoost

**Libraries**: Numpy, Pandas, Matplotlib, XGBoost, Seaborn

**Overview:**

a. Data preprocessing - checking for null values

b. Data analysis and representation using Matplotlib.

c. Hyperparameter tuning and Pipelining using XGBoost.

d. Comparison of accuracy derived by different hyperparameter combinations using Grid Search, Random Search and Bayesian Optimization.


### 3.	Breast Cancer Prodiction ###
**Objective:** Multi-class model in Machine Learning

**Libraries:** Scikit-learn, Numpy, Pandas, Matplotlib, Seaborn

**Overview:**

a. Pre-processing data, like checking for null values and drop unwanted columns, and standardizing all values using Scikit-learn (sklearn)

b. Performing PCA for dimensionality reduction. 10 out of 30 columns are enough to explain 95% of variance.

c. Training and Testing the data with these 10 columns.

d. Utilizing default classifiers for below machine learning algorithms:

    Descision Tree Classifier
    Random Forest Classifier
    XGB (eXtreme Gradient Boosting) Classifier
    Gradient Boosting Classifier
    Extra Trees Classifier
    K-nearest Neighbors Classifier

e. Training the data with all the above classifiers

f. Testing the data, making predictions and calculating accuracy accordingly.

g. Using a confusion matrix to evalute the performance of all classifiers.

h. Representing and comparing all classifier performances with a ROC curve.



### 4.	Newton-Raphson ###
**Objective:** Newton-Raphson mathematical representation using Python

**Libraries:** SciPy, Math, Sympy, Numpy, Matplotlib

**Overview:**

a. Define a function using Math

b. Calculating derivative of the function to determine critical points
c. Using SciPy’s built-in Newton’s algorithm  for optimization of given function.
d. The code is a representation of mathematical calculations performed in Question (1.c): https://github.com/uttara-tech/typesetting-LaTeX/blob/8fbead2715a8d54141a1f6b09b3e073e6d3bd9a7/linear_algebra/Mid_Module_Assignment.pdf

    Repository - typesetting-LaTeX
    Folder - linear_algebra
    File - Mid_Module_Assignment.pdf, Question (1.c)
    


### 5.	Video Games sales data analysis ###
**Objective:** Data Visualization

**Libraries:** Numpy, Pandas, Matplotlib, Seaborn

**Overview:**

a. Exploring and grouping the data.

b. Data visulalization using Matplotlib and Seaborn.

c. Used Heatmap, Histogram, Count plot, Bar plot, Group Bar plot, Joinplot.



### 6.	Students Performance ###
**Objective:** Data Visualization

**Libraries:** Numpy, Pandas, Matplotlib, Seaborn

**Overview:**

a. Exploring and grouping the data.

b. Data visulalization using Matplotlib and Seaborn.

c. Used Distribution plot, Join plot, Pair plot, Box plot, Heatmap, Seaborn’s ‘catplot’ i.e.  plot showcasing relationship between numerical and categorical variables i.e. catplot, Count plot, Bar plot.

