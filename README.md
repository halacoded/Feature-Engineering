# Titanic Survival Prediction

## Overview  
Titanic Survival Prediction is a machine learning project designed to predict whether a passenger survived the Titanic disaster based on various personal and travel-related features. This model demonstrates essential data science practices such as data preprocessing, feature engineering, and classification.

## Dataset  
The dataset used for training is `Titanic.csv`, which contains the following columns:

- `Survived`: Target variable (1 = Survived, 0 = Did not survive)  
- `Pclass`: Ticket class (1st, 2nd, 3rd)  
- `Name`: Passenger name  
- `Sex`: Gender  
- `Age`: Age of the passenger  
- `SibSp`: Number of siblings/spouses aboard  
- `Parch`: Number of parents/children aboard  
- `Ticket`: Ticket number  
- `Fare`: Ticket fare  
- `Cabin`: Cabin number  
- `Embarked`: Port of embarkation

## Objectives  

- Develop a classification model to predict passenger survival.  
- Apply feature engineering techniques.  
- Handle missing data and encode categorical variables.  
- Evaluate model performance using accuracy, precision, recall, and F1-score.

## Feature Engineering  

The following new features were created:

- `Title`: Extracted from the `Name` column (e.g., Mr, Mrs, Miss, etc.)  
- `FamilySize`: Sum of `SibSp` and `Parch` plus 1 (self)  
- `IsAlone`: Indicates whether the passenger was traveling alone (`FamilySize == 1`)

## Model Evaluation  

The model is evaluated using the following metrics:

- Accuracy  
- Precision  
- Recall  
- F1-score
- 
## Installation and Usage

### Prerequisites  
- Python 3.x  
- Google Colab or Jupyter Notebook  
- Required libraries:
  - pandas  
  - numpy  
  - scikit-learn  
  - matplotlib  
  - seaborn

### Setup  
Click COLAP Link And Downalod Dataset then You are Ready to start


