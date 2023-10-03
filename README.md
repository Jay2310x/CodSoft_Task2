# CodSoft_Task2
Task 2 performed at CodSoft Internship period

### **Aim**
The aim of this project is to predict sales of a Car based on a  consumers would spend given the following characteristics:
customer name, customer email, country, gender, age, annual salary, credit card debt, and net worth

### **Libraries Used**
The following important libraries were used for this project:

numpy
pandas
matplotlib.pyplot
seaborn
sklearn.model_selection.train_test_split
from sklearn.preprocessing import MinMaxScaler

### **Dataset**
The dataset was loaded using pandas as a DataFrame from the file "advertising.csv".

### **Data Exploration and Preprocessing**
-The shape and descriptive statistics for the dataset were displayed using df.shape and df.describe().
-A pair plot was created to visualize the relationship between advertising expenditure Training and Validation Loss and Training and Validation Accuracy using seaborn.pairplot.
-Histograms were plotted to observe the distribution of advertising expenditure on age, anual salary, Credit card debt, and networth using  sns.distplot().

### **Model Training**
The data was split into training and testing sets using train_test_split.
Linear regression model was trained on the training data using sklearn.linear_model.MinMaxScaler


### **Model Prediction**
The model was used to predict sales based on advertising expenditure on Car for the test set using model.predict(X_test) and the corresponding advertising expenditure on car in the test set.
The model coefficients and intercept were obtained using model.coef_ and model.intercept_.
The predictions and actual sales values were plotted using matplotlib.pyplot.plot and matplotlib.pyplot.scatter.
