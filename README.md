# ☀️ Weather-Driven Solar Energy Forecasting

This is a machine learning project developed as part of a group research project for the BSc (Hons) in Data Science and Business Analytics at General Sir John Kotelawala Defence University.

The project focuses on building an accurate and efficient solar power output prediction system for the **Vydexa Solar Power Plant** in Vavuniya, Sri Lanka, by using real-world operational and weather data.

---

## 📌 Project Overview

The main goal of this project is to forecast **short-term (15 minutes)** and **long-term (1 hour)** solar power output using machine learning techniques.

By integrating solar plant operational data with local weather data, the model helps:
- Improve energy planning
- Enhance power grid stability
- Reduce operational uncertainty

---

## 🔍 Objectives

- Acquire and clean solar and weather datasets
- Perform exploratory data analysis (EDA)
- Train and evaluate ML models like:
  - Lasso Regression
  - Random Forest
  - XGBoost
  - LSTM (Neural Network)
- Deploy the best model using a simple interface (e.g., Streamlit)

---

## 🧠 Machine Learning Models Used

| Model              | Type           | Purpose                             |
|-------------------|----------------|-------------------------------------|
| Lasso Regression  | Linear         | Baseline model, simple & interpretable |
| Random Forest      | Ensemble Trees | Good for handling non-linear data   |
| XGBoost            | Boosted Trees  | High performance with tuning        |
| LSTM               | Deep Learning  | Excellent for time-series forecasting|

---

## 🛠️ Technologies Used

- **Python**
- **Pandas, NumPy, Scikit-learn**
- **TensorFlow, Keras**
- **XGBoost**
- **Matplotlib, Seaborn**
- **Google Colab & VS Code**
- **Power BI & R Studio** (for visualization and statistics)
- **Streamlit** (for model deployment)

---

## 📁 Folder Structure

```text
solar-energy-forecasting/
├── data/               ← (Not included – contains private operational and weather data)
├── notebooks/          ← Jupyter Notebooks for EDA and modeling
├── src/                ← Python scripts for training and utils
├── app/                ← Deployment files (e.g., Streamlit app)
├── reports/            ← Graphs, figures, and evaluation plots
├── README.md           ← Project explanation (this file)
├── requirements.txt    ← List of Python libraries used
└── Final_Report.pdf    ← Project documentation/report
````

> ⚠️ Note: Due to privacy and data protection policies, the `data/` folder is not included in this repository.

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/solar-energy-forecasting.git
cd solar-energy-forecasting
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Models (Optional)

```bash
python src/train_models.py
```

### 4. Launch the Streamlit App

```bash
streamlit run app/streamlit_app.py
```

---

## 📊 Results Summary

All models were evaluated on:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score (Coefficient of Determination)

**Best performing model:** LSTM
**Best for simplicity & interpretability:** Lasso Regression
**Best balance of accuracy & speed:** XGBoost

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍🎓 Authors

* HMRV Herath – D/DBA/22/0002
* RN Silva – D/DBA/22/0007
* TM Kahavidhana – D/DBA/22/0017
* KT Panditha – D/DBA/22/0028

> Supervised by Mrs. SMM Lakmali
> Department of Computational Mathematics
> General Sir John Kotelawala Defence University




