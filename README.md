# Predicting_Gestation_Time
ML Classification Algorithms

Source of dataset: https://wonder.cdc.gov/natality-current.html

The CDC Wonder natality dataset is a comprehensive and diverse source of information on 
maternal health complications across the United States. This dataset includes a wide range of 
variables, such as states including all 50 states in the US, pregnancy-associated hypertension in 
mother, delivery method such vaginal or caesarean, diabetes, eclampsia, number of births, 
percentage of total births, average birth weight, the standard deviation for average birth weight, 
the average age of mother, the standard deviation for the average age of mother, the standard 
deviation for average LMP gestational age, and prediction for gestation term.
Here, the Target variable is the "Prediction for Gestation Term", which is classified as early-term, 
full-term, or late-term based on CDC and Cleveland Clinic guidelines. This variable is the one we 
are trying to predict using the independent variables.
The Independent variables are the other variables in the dataset that may impact the prediction 
of the gestation term. These include "State", Pregnancy-associated Hypertension", "Delivery 
Method", "Diabetes", "Eclampsia", "Births" "Percentage of Total Births", "Average Birth Weight", 
"Standard Deviation for Average Birth Weight", "Average Age of Mother", and "Standard 
Deviation for Average Age of Mother".
This data was collected from the CDC Wonder natality reports for the last 10 years between 2012-
2021. I selected the necessary collections by using the options in the drop-down menus provided 
on the request form. I did various data visualizations on Google spreadsheets to filter out the 
redundant data and collected the most significant variables necessary for the best inputs to the 
machine learning model.
My focus will be on extracting insights that can help predict the gestation time from conception to 
delivery, a critical factor in ensuring the well-being of both mother and child. To achieve this goal, 
I will employ state-of-the-art machine learning techniques. Using a supervised classification 
approach, I will train the model to predict the gestation term, which will be classified as an early 
term, full-term, or late-term based on the guidelines provided by the CDC.
The dataset comes with its own set of challenges, I plan to perform EDA for addressing missing 
values and categorical data that needs to be transformed into numerical data using one hot
encoding. To gain further insights into the data, I will use techniques such as univariate analysis, 
heat maps, and box plots for finding the correlation between the input variables. I plan on
performing extensive data preprocessing, including feature engineering, and splitting the data.
With a dataset of 1000 samples, I plan to split the data into testing and training sets using an 80:20 
split, providing ample opportunity for thorough experimentation and analysis.
I plan to experiment with several classification algorithms, including decision trees, random 
forests, support vector machines, and K-nearest neighbors, to determine the best approach for this 
classification problem. To evaluate the performance of each algorithm, I will use a combination of 
accuracy, ROC and AUC, and confusion matrix metrics. I anticipate that my approach will yield 
promising results, given the rich and diverse nature of the CDC Wonder dataset. Overall, my
project aims to contribute to the growing body of knowledge in the field of machine learning, while 
also providing valuable insights into maternal health and wellbeing.
