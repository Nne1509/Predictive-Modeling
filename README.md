PREDICTIVE MODELLING FOR AGRICULTURE

OVERVIEW
This repository contains the code and resources for a machine learning model that helps a farmer to decide the best crops to plant in his field based on the condition of the soil. This model analyzes soil metrics such as Nitogen, Potassium, Phosphorous and pH levels of the soil to assist the farmer in making the best decision.

Data
The dataset used for the model is named soil_measures.csv and contains the following colums which have been preprocessed and prepared to build the machine learning model:
1. "N": Nitrogen content ratio in the soil
2. "P": Phosphorous content ratio in the soil
3. "K": Potassium content ratio in the soil
4. "pH": pH value of the soil
5. "crop": Categorical values representing various crops (target variable).

Data Exploration
The data exploration for this project consisted of the following:
1. Handling missing values
2. Crop Identification
3. Feature Correlation

Model Development
The aim of this project was to build a multi-class classification model to predict suitable crops for the farmer. We employed logistic regression to achieve this and plotted a heat map to guide our feature selection in order to avoid multicollinearity.

Model Evaluation
We evaluated the performance of our model using F-1 scores and the results can be found in the Jupyter Notebook.

Results
The project succeeded in assisting the farmer to make an informed data-driven decision leading to improved yields and productive farming practices. The results prove the viability of machine learning in crop selection and provide insights on how agricultural practices can be improved.

Conclusion
This project demonstrates the potential of machine learning in agriculture. By capitalizing on data available, we can help farmers make more sustainable and profitable decisions.