# Car-Price-Prediction
Description
This Python project utilizes advanced Machine Learning techniques to predict the prices of used cars using datasets sourced from PakWheels. The datasets include various attributes such as car model, manufacturer, mileage, and geographical locations within Pakistan. By employing libraries like Pandas, Scikit-learn, and Plotly, this project offers insights through interactive visualizations and predicts car prices based on specific parameters. The project also incorporates preprocessing methods to address missing data and outliers, enhancing the accuracy of price predictions.

Table of Contents
Introduction
Objectives
Data Preprocessing
Exploratory Data Analysis
Modeling
Results
Conclusions and Recommendations
Acknowledgements
Introduction
This project aims to leverage the capabilities of machine learning to accurately predict used car prices in Pakistan. Utilizing comprehensive datasets from PakWheels, the project has achieved an impressive predictive accuracy of 96%.

Objectives
Design a state-of-the-art predictive model to estimate used car prices in the Pakistani market.
Analyze the factors influencing automobile valuations.
Provide an intuitive digital interface for accessible car price estimations.
Data Preprocessing
Data Cleaning
Applied exhaustive cleaning to structure JSON data and remove superfluous attributes.
Addressed missing values to preserve data integrity.
Feature Engineering
Extracted engine capacities from descriptions.
Refined location data for detailed geographic insights.
Exploratory Data Analysis
Visual Insights
Correlation Matrix: Showed relationships between car models and market valuations.
Bar Charts: Depicted engine capacity popularity.
Pie Charts: Detailed car assembly by manufacturer.
Line Graph: Traced car sales trends over various model years.
Choropleth Map: Illustrated vehicle sales across Pakistani cities.
Histograms: Highlighted prevalent car body types and colors.
Modeling
Model Construction
Utilized the XGBoost Regressor to capture nonlinear relationships between features and the target variable.
Employed R2 scores and cross-validation to ensure robustness and generalizability.
Pipeline Integration
Integrated preprocessing with model training to streamline data transformation and model assessment.
Results
The predictive model demonstrated exemplary performance with a high R2 score. A Streamlit application was developed to provide users with real-time price predictions based on input features.

Conclusions and Recommendations
The project culminated in a highly accurate predictive model that forecasts prices and provides insights into market dynamics. Future research recommendations include:

Expanding the dataset for broader applicability.
Investigating ensemble methods for potentially superior predictions.
Exploring feature importance to understand key influencers of car prices.
Acknowledgements
Gratitude is extended to:

Kaggle for providing datasets.
Stack Overflow and GitHub for community support and code repositories.
ChatGPT for AI-driven insights.
Getting Started
Prerequisites
Python 3.x
Libraries: Pandas, Scikit-learn, Plotly, XGBoost, Streamlit
Installation
Clone the repository:
sh
Copy code
git clone https://github.com/yourusername/used-car-price-prediction.git
Navigate to the project directory:
sh
Copy code
cd used-car-price-prediction
Install the required dependencies:
sh
Copy code
pip install -r requirements.txt
Usage
Run the Streamlit application:
sh
Copy code
streamlit run app.py
Follow the instructions to input car attributes and get price predictions.
License
This project is licensed under the MIT License - see the LICENSE file for details.
