# Breast Cancer Survival Model

This model aims to predict the survival of breast cancer patients based on various features such as patient demographics, protein expression levels, tumor stage, histology and treatment history.

## Table of Contents 
- [Dataset](#dataset)
- [Exploratory Data Analysis](#EDA)
- [Prediction Model](#Predictionmodel)
- [Results](#results)
- [Dependencies](#Dependencies)
- [Usage](#Usage)
- [Contributions](#Contributions)

  #### Dataset
  The dataset contains information aobut over 400 breast cancer patients who have unfergone durgery for treatment. The data includes
    - patient ID
    - age
    - gender
    - protein expression levels
    - tumor stage
    - histology
    - ER status
    - PR status
    - HER2 status
    - surgery type
    - date of surgery
    - date of last visit
    - patient status(alive or dead)
 
  #### Exploratory Data Analysis
  The initial steps of the model involve exploring the dataset to gain insights into the distribution of various features. Exploratory data analysis includes
    - data cleaning
    - handling missing values
    - visualization of:
          - tumor stages
          - histology
          - ER/PR/HER2 status
          - types of surgeries performed on patients

  #### Prediction Model
  [Support Vector Classifier(SVC)](https://scikit-learn.org/stable/modules/svm.html) is used to build the predictive model. The model is trained on a set of features extracted from the dataset.
  Hyperparameter tuning is performed using grid search and the best parameters are selected to optimaize the model.
  The performance of the model is evaluated using classification metrics such as precision, recal, and F1-score.

  #### Results
  The model achieves an accuracy of 85% in predicting the survival of breast cancer patients.

  #### Dependencies
  The model uses the following dependencies
  - [pandas](https://pandas.pydata.org/docs/user_guide/index.html)
  - [numpy](https://numpy.org/doc/stable/user/index.html)
  - [plotly](https://plotly.com/python/getting-started/)
  - [scikit-learn](https://scikit-learn.org/stable/user_guide.html)
 
  #### Usage
  To run this model, ensure that the required dependencies are installed.
  The execute the jupyter notebook 'breastcancersurvival.ipynb' in your preferred environment.
  Make sure the dataset file 'BRCA.csv' is located in the same directory as the notebook.

  #### License
  This project is licensed under the MIT License - see the [LICENSE](https://github.com/akosaraju19/Breastcancersurvival/blob/main/LICENSE) file for details.
