# COVID-19 Recovery Forecasting: Symptom-Based Machine Learning Model

This project focuses on predicting whether a person is likely to recover from coronavirus symptoms based on pre-defined standard symptoms. The dataset used contains daily-level information on the number of affected cases, deaths, and recoveries from the 2019 novel coronavirus since January 22, 2020. The data is available in 'data.csv'. It is important to note that this is a time series dataset, and the number of cases on any given day is cumulative.

## Dataset Description

The dataset contains 14 major variables that impact whether someone has recovered or not. Here's a brief description of each variable:

1) Country: The country where the person resides.
2) Location: The specific location within the country.
3) Age: Classification of the age group based on WHO Age Group Standard.
4) Gender: Male or Female.
5) Visited_Wuhan: Whether the person has visited Wuhan, China, or not.
6) From_Wuhan: Whether the person is from Wuhan, China, or not.
7) Symptoms: Six families of symptoms coded in six fields.
13) Time_before_symptoms_appear: Time before symptoms appear.
14) Result: Death (1) or recovered (0).


## Project Objective


The objective of this project is to design different classifiers to predict the outcome (death/recovered) when a new person is admitted to the hospital. The dataset is already cleaned and preprocessed.

## Classifiers included

1) Support Vector Machines
2) K-Nearest Neighbors
3) Bayes Classifier
4) Decision Trees
5) Multi-Layer Perceptron

## Author
Shehab Adel Ramadan
## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/)
