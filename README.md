
# ⚡ PowerPulse: Household Energy Usage Forecast

**PowerPulse** is a machine learning project aimed at forecasting household electricity usage using historical consumption data. It compares several regression models to determine the best performer and supports energy-efficient insights for households and providers.

---

## 🚀 Project Objectives

- Predict household energy usage accurately using machine learning models.
- Analyze and visualize power usage trends over time.
- Compare multiple regression algorithms and select the best.
- Save the best-trained model for deployment or future inference.

---

## 📊 Features

- ✔️ Data preprocessing and missing value handling
- ✔️ Feature engineering (rolling averages, time-based features)
- ✔️ Model training:
  - Linear Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - Gradient Boosting
- ✔️ Evaluation using RMSE, MAE, and R²
- ✔️ Visualizations for trends and model comparisons
- ✔️ Saves the best-performing model to a `.pkl` file

---

## 📁 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)
- **File Name**: `household_power_consumption.txt`
- **Duration**: 2006 to 2010
- **Sampling Rate**: 1-minute intervals

---

## 📦 Project Structure

```
PowerPulse_Energy_Forecast/
│
├── data/
│   └── household_power_consumption.txt       # Raw dataset (not included)
│
├── models/
│   └── Best_Model_Name_model.pkl             # Saved best model (after training)
│
├── notebooks/
│   └── PowerPulse_Forecast_Project.ipynb     # Jupyter notebook with full pipeline
│
├── README.md                                 # Project description and usage
└── requirements.txt                          # List of Python dependencies
```

---

## 🛠 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/PowerPulse_Energy_Forecast.git
cd PowerPulse_Energy_Forecast
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🧠 How to Use

> Make sure `household_power_consumption.txt` is placed inside the `data/` folder.

### 1. Open Jupyter Notebook

```bash
jupyter notebook notebooks/Project3.ipynb
```

### 2. Run the Notebook
- Performs data cleaning and feature engineering.
- Trains multiple models and compares their accuracy.
- Saves the best model based on RMSE to `/models`.

---

## 📈 Evaluation Metrics

| Metric        | Description                                  |
|---------------|----------------------------------------------|
| RMSE          | Measures prediction error magnitude          |
| MAE           | Average absolute difference from real value  |
| R² Score      | Proportion of variance explained             |

---

## 📊 Visualizations

- Power usage trend over time
- Feature importance (tree-based models)
- Model performance comparison (bar charts)

---

## 📄 License

This project is licensed under the MIT License.

---
##👨‍💻 Author
Name: [SHREE PURVAJA D]

##Contact Me Through
LinkedIn:[shree-purvaja-d][https://www.linkedin.com/in/shree-purvaja-d/]

Email: [shreepurvaja@gmail.com]


