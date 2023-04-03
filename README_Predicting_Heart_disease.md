### Sumeet Shah

### Predicting Heart disease

### Topic: Predicting heart problems in patients using Machine learning

### Project overview:

According to the World Health Organization, cardiovascular disease (CVD) is the top cause of death worldwide. In 2015, over 30% of global deaths were due to CVD, leading to over 17 million deaths. Data Science and machine learning (ML) can be very helpful in the prediction of heart attacks in which different risk factors like high blood pressure, high cholesterol, abnormal pulse rate, diabetes, etc. can be considered. The goal of this project is to use statistical learning to identify the combination of the factors that are more likely to be associated with heart failure and predict whether a patient will get heart attack based on the given attributes. Early prognosis of cardiovascular diseases can aid in making decisions on lifestyle changes in high-risk patients and in turn reduce the complications.

The dataset used in this project is from Framingham Heart study. I have used Python 3.6 for this project, and have used Python libraries like pandas, numpy, matplotlib, sklearn, seaborn, Logistic regression and KNN. I started with Logistic regression initially as; logistic regression is the first choice for any binary classifier problems. Logistic regression is a statistical method that is used for building machine learning models where the dependent variable is dichotomous: i.e. binary. I have also used KNN to predict heart disease in patients. Then I have compared the two models with various metrics like AUCROC, Confusion Matrix and Model Accuracy. 

The project focuses on performing Exploratory data analysis on the dataset, visualizing the attributes and getting an idea of attributes that are correlated. I have plotted histograms and Scatter plots to get idea of these correlations. A correlation matrix is plotted via heatmap to see which attributes have direct relation with 10 year Coronary heart disease. Then those attributes are used to build models with Logistic regression. The data set was split into test and train, and the model was trained on training dataset, and then predictions were tested on test dataset.

### Project Install and Technologies

The dataset is available at Kaggle:
https://www.kaggle.com/datasets/dileep070/heart-disease-prediction-using-logistic-regression

The Python notebook includes the code for the project. The various tools used for the project are:

      1.Anaconda
      2.Jupyter Notebook
      3.Python 3.6
      
The .ipynb file lists the different data science python libraries used throughout the project.

### Licence

MIT License

Copyright (c) 2023 Sumeet Shah

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
