# Weather-Driven-Solar-Energy-Forecasting
This is a machine learning project developed as part of a group research project for the BSc (Hons) in Data Science and Business Analytics at General Sir John Kotelawala Defence University.  The project focuses on building an accurate and efficient solar power output prediction system by using real-world operational and weather data.

## Project Overview

The main goal of this project is to forecast **short-term (15 minutes)** and **long-term (1 hour)** solar power output using machine learning techniques.

By integrating solar plant operational data with local weather data, the model helps:
- Improve energy planning
- Enhance power grid stability
- Reduce operational uncertainty

## Objectives

- Acquire and clean solar and weather datasets
- Perform exploratory data analysis (EDA)
- Train and evaluate ML models like:
  - Lasso Regression
  - Random Forest
  - XGBoost
  - LSTM (Neural Network)
- Deploy the best model using a simple interface (e.g., Streamlit)

## Machine Learning Models Used

| Model              | Type           | Purpose                             |
|-------------------|----------------|-------------------------------------|
| Lasso Regression  | Linear         | Baseline model, simple & interpretable |
| Random Forest      | Ensemble Trees | Good for handling non-linear data   |
| XGBoost            | Boosted Trees  | High performance with tuning        |
| LSTM               | Deep Learning  | Excellent for time-series forecasting|

## Technologies Used

- **Python**
- **Pandas, NumPy, Scikit-learn**
- **TensorFlow, Keras**
- **XGBoost**
- **Matplotlib, Seaborn**
- **Google Colab & VS Code**
- **Power BI & R Studio** (for visualization and statistics)
- **Streamlit** (for model deployment)

## 📁 Folder Structure

```text
solar-energy-forecasting/
├── data/               ← Raw and processed datasets
├── notebooks/          ← Jupyter Notebooks for EDA and modeling
├── src/                ← Python scripts for training and utils
├── app/                ← Deployment files (e.g., Streamlit app)
├── reports/            ← Graphs, figures, and evaluation plots
├── README.md           ← Project explanation (this file)
├── requirements.txt    ← List of Python libraries used
└── Final_Report.pdf    ← Project documentation/report

