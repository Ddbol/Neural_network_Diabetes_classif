# Predict Diabetes From Medical Records- Neural Network model investigation

Dataset: Several medical features given with the output of whether patient is diabetic or not.  

Objective: Compare performance of an artificial neural network (ANN) to other supervised classification models to predict diabetic or not 

Summary: Conducted an exploratory data analysis and cleaned data, logging some skewed features. Regularised data using scaling. Ran logistic regressionof original and data with logged features, which performed better. Ran SVM and various complexity (binary preceptron, 1 hidden layer, 3 hidden layers) neural network models on data with logged features. Early stopping rather than fixed epochs resulted in slightly higher accuracy models compared to logistic regression or SVM but at much higher time and computational cost. 

Tools used: Python, pandas, numpy, matplotlib, seaborn, scikitlearn, regularisation (scaling), logistic regression, SVM, neural networks

Files:

Comparing_neural_networks1.PNG, Comparing_neural_networks2.PNG - Images to display in ipynb files

neural_network_diabetes_DBoland_Feb25.ipynb - main code

neural_network_diabetes_DBoland_Feb25.pdf - Pdf of presentation of data analysis, visualisation and supervised ML and neural networks

neural_network_diabetes_DBoland_Feb25.ipyn.pptx - Presentation of data analysis, visualisation and supervised ML and neural networks (View raw to view online and interact with links)

diabetes.keras, scaler.pkl, logreg.pkl - neural network model fit, scaled data fit and logistic regression model fit saved for use with new data sets or to build online streamlit application

diabetes.csv - data input.
