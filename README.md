# TASK
### What is the problem?

Breast cancer is the most common disease among women. Define it using the given parameters.
Description - Breast cancer is a common disease in women worldwide. It accounts for 25% of all cancers. Breast cancer starts when cells in the breast grow out of control. These cells are usually detected by examining tumors that can be seen on X-rays.

# DESCRIPTION
### How have you solved the problem?

I did this project in 7 steps.
Load Dataset
Summarizing the dataset
Visualization
Correlation
Preparation for Machine Learning
Machine Learning
Model evaluation
In the Load Dataset section, the data is transferred to the DataFrame view.
In the section Summarizing the dataset, the function summarize dataset() was used, which prints general information about the DataFrame.
The Visualization Section DataFrame columns are visualized. The relationship between the columns is reflected in the visual representation.
In the correlation section, changed letter columns to numeric columns using LabelEncoder from sklearn. Then, correlations were checked across all columns. The columns with the highest correlation were identified.
In the Preparation for Machine Learning section, the data was separated into X(X parameters) and y(label) to prepare the data for machine learning. The extracted data were then standardized (StandardScaler(), fit_transform(X)).
In the machine learning section, the data is split into train_set and test_set using train_test_split in sklearn. Then f1_score in sklearn and GridSearchCV in sklearn were used to find the value of k(nearest n neighbors) needed to run the KNN(KNeighborsClassifier) algorithm. A knn model was then created using the KNeighborsClassifier included in sklearn.
In the model evaluation part, several methods were used to evaluate our model. These are Jaccard index, Confusion matrix, Precision, recall, F1 and Cross validation.

# INSTALLATION
### How to install project? npm install? Make re?

To run the program in the jupyter notebook, you need to import the pandas, numpy, matplotlib, seaborn and sklearn packages.

# USAGE
### How does it work?

the program is run through jupyter notebook.
