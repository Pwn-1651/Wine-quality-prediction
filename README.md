Overview

Wine Price Prediction is a Machine Learning project that estimates the market price of wine based on various characteristics such as quality, alcohol content, acidity, vintage year, region, and other chemical properties. The project uses data analysis and regression techniques to provide accurate price predictions, helping businesses and consumers make informed decisions.

Features
Data preprocessing and cleaning
Exploratory Data Analysis (EDA)
Feature engineering and selection
Machine learning regression models
Model evaluation and performance metrics
Wine price prediction for new data
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
Dataset

The dataset contains wine attributes such as:

Quality Score
Alcohol Content
Acidity
Residual Sugar
Density
pH Level
Sulphates
Region
Vintage Year
Price (Target Variable)
Project Structure
Wine-Price-Prediction/
│
├── data/
│   └── wine_data.csv
│
├── notebooks/
│   └── wine_price_prediction.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── requirements.txt
├── README.md
└── app.py
Installation
Clone the repository:
git clone https://github.com/your-username/Wine-Price-Prediction.git
Navigate to the project directory:
cd Wine-Price-Prediction
Install dependencies:
pip install -r requirements.txt
Usage

Run the Jupyter Notebook:

jupyter notebook

Or run the application:

python app.py
Machine Learning Workflow
Load and clean the dataset
Perform Exploratory Data Analysis (EDA)
Handle missing values and outliers
Select important features
Train regression models
Evaluate model performance
Predict wine prices on new data
Evaluation Metrics
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
Results

The trained model analyzes wine characteristics and predicts prices with high accuracy. Performance may vary depending on dataset quality and feature selection.

Future Improvements
Deploy the model using Flask or Streamlit
Add real-time prediction interface
Experiment with advanced algorithms
Improve prediction accuracy with larger datasets
Author

Developed as a Machine Learning project using Python and data science techniques for wine price forecasting.

License

This project is licensed under the MIT License.
