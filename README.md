# ENEL 645 - Data Mining & Machine Learning
### Assignment 1

The task in this assignment is to apply a linear regression model to the "Community Crime and Disorder Statistics" dataset, sourced from Open Calgary.

The goal is to train a model to predict the number of crimes in each community center based on various input features, using a linear regression model with multiple input features. The output variable, or target, is the 'Crime Count'. The performance of the model is evaluated based on the Mean Squared Error (MSE) cost function.

The dataset was split into a training set (70% of the data) and a test set (30% of the data). The linear regression model was then trained on the training set, and its performance was evaluated on the test set.

The 'Community name' was considered as the index column of the dataset. Categorical variables were converted into dummy/indicator variables using pandas' get_dummies() function. Feature engineering was also applied to achieve better results.

The Python code for this assignment is provided in .ipynb format. A descriptive report about the algorithm, methodology, and results is also included in this repository.

## Folder Structure 
<!-- - [A1 Instructions](https://github.com/StevenD24/ENSF-614-Lab-6/blob/main/ENSF%20614%20-%20Lab%206.pdf)    -->
- [A1 Report](https://github.com/StevenD24/ENEL-645-Assignment-1/blob/main/ENEL%20645%20-%20Assignment%201%20Report.pdf)  
- [A1 Notebook](https://github.com/StevenD24/ENEL-645-Assignment-1/blob/main/A1_Linear_Regression.ipynb) 
