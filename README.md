# README

## Project Title: Predicting Students' Gender Based on Academic Performance and Socio-Demographic Factors

Welcome to the Gender Prediction Project! This project aims to predict students' gender (male or female) using their scores in math, reading, and writing, as well as additional socio-demographic factors such as lunch type, race/ethnicity, test preparation course completion, and parental level of education.

### Table of Contents

- [Introduction](#introduction)
- [Data Description](#data-description)
- [Data Preprocessing](#data-preprocessing)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [Dependencies](#dependencies)
- [How to Use](#how-to-use)

### Introduction

In this project, I leverage machine learning algorithms to predict students' gender based on their academic scores and socio-demographic attributes. This analysis could provide insights into the relationships between these factors and gender, and help in identifying any potential biases in educational performance.

### Data Description

The dataset used in this project includes the following features:
- **Gender**: 1 for male, 0 for female (target variable).
- **Math Score**: Students' scores in math.
- **Reading Score**: Students' scores in reading.
- **Writing Score**: Students' scores in writing.
- **Lunch**: 1 for standard, 0 for free/reduced.
- **Race/Ethnicity**: Encoded from 1 to 5.
- **Test Preparation Course**: 1 if completed, 0 otherwise.
- **Parental Level of Education**: Encoded from 0 to 5, representing different levels of education.

### Data Preprocessing

To prepare the data for modeling, the following preprocessing steps were performed:
- Conversion of categorical variables to numeric values.
- Creation of additional features such as average score and combined writing & reading skills.

### Model Training and Evaluation

I implemented and evaluated several machine learning algorithms to identify the best performing model. The following models were used:
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Random Forest**
- **Naive Bayes**

Each model was trained using the training set and evaluated using the test set. I also tuned hyperparameters to improve the models' performance.

### Results

The evaluation of models included calculating accuracy, f-beta scores, and ROC-AUC scores. The models' performance before and after tuning was compared to ensure improvement. Visualization of confusion matrices and ROC curves was used to assess the models' predictive capabilities.

### Conclusion

The project successfully demonstrated the use of machine learning techniques to predict students' gender based on academic performance and socio-demographic factors. The best-performing model after hyperparameter tuning was the K-Nearest-Neighbor classifier with an accuracy of approximately 90%.

### Dependencies

This project requires the following libraries:
- pandas
- numpy
- seaborn
- scikit-learn
- matplotlib
- scikitplot
- termcolor

You can install the dependencies using the following command:
```bash
pip install pandas numpy seaborn scikit-learn matplotlib scikitplot termcolor
```

### How to use
1. Clone the repository:
```
git clone https://github.com/AviRahimov/Data-science-project.git
```
2. Run the main script to preprocess data, train models, and evaluate results:
```
pip install jupyter
```
```
jupyter notebook DataScience Project - Students performance (2).ipynb
```

Enjoy exploring the world of machine learning and gender prediction with this project!
For any questions or contributions, feel free to open an issue or submit a pull request.
Happy Coding!
