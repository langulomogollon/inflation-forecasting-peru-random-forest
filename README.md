# 📈 Inflation Forecasting in Peru using Random Forest

Machine Learning project focused on forecasting inflation in Peru using macroeconomic indicators and the Random Forest regression algorithm. The objective is to analyze economic data and generate accurate inflation predictions to support economic and financial decision-making.

## 🚀 Project Overview

Inflation forecasting is a key task for governments, central banks, and financial institutions. In this project, historical economic data from Peru is used to train a Random Forest model capable of predicting future inflation trends.

The project includes:

- Data collection and preprocessing.
- Exploratory Data Analysis (EDA).
- Feature engineering.
- Random Forest model training and optimization.
- Model evaluation and performance analysis.
- Inflation forecasting visualization.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Databricks IDE

## 📊 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Selection
5. Model Training (Random Forest Regressor)
6. Hyperparameter Tuning
7. Model Evaluation
8. Inflation Forecast Generation

## 📂 Project Structure

```bash
inflation-forecasting-peru-random-forest/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── inflation_forecasting.ipynb
│
├── images/
│   └── forecast_results.png
│
├── src/
│   ├── preprocessing.py
│   ├── training.py
│   └── forecasting.py
│
├── requirements.txt
└── README.md
```

## 📈 Model Performance

The Random Forest model was evaluated using regression metrics such as:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

Results demonstrated the model's ability to capture inflation patterns from historical economic indicators.


## 🎯 Key Insights

- Random Forest effectively captures non-linear relationships in economic data.
- Feature importance analysis helps identify the variables with the greatest influence on inflation.
- The model can serve as a complementary forecasting tool for economic analysis.

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/inflation-forecasting-peru-random-forest.git
```

Navigate to the project folder:

```bash
cd inflation-forecasting-peru-random-forest
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Usage

Run the notebook:

```bash
jupyter notebook
```

Or execute the training script:

```bash
python src/training.py
```

## 📚 Future Improvements

- Incorporate additional macroeconomic variables.
- Compare Random Forest with XGBoost and LightGBM.
- Deploy the model using Streamlit.
- Automate data updates from official economic sources.

## 👨‍💻 Author

Leonardo Martín Angulo Mogollón

Data Analyst | Business Intelligence | Databricks Certified


