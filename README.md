# Laptop Price Prediction using Machine Learning
A machine learning project that predicts laptop prices based on specifications such as brand, processor, RAM, storage, GPU, and display features. Multiple regression models were trained and compared to identify the best-performing model.

## Features
* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model training and evaluation
* Hyperparameter tuning
* Laptop price prediction

## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Models Used
* Linear Regression
* KNN Regressor
* Support Vector Regressor (SVR)
* Random Forest Regressor
* Gradient Boosting Regressor

## Results

| Model             | R² Score |
| ----------------- | -------- |
| Gradient Boosting | 0.9858   |
| Random Forest     | 0.9115   |
| SVR               | 0.8318   |
| KNN               | 0.7806   |
| Linear Regression | 0.7768   |

**Best Model:** Gradient Boosting Regressor (98.58% Accuracy)

## How to Run
git clone https://github.com/your-username/Laptop-Price-Prediction.git
cd Laptop-Price-Prediction
pip install -r requirements.txt
jupyter notebook

## Project Structure
Laptop-Price-Prediction/
├── Laptop_Price_Prediction.ipynb
├── dataset.csv
├── README.md
└── requirements.txt
