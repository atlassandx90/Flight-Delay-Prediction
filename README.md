# ✈️ Flight Delay Prediction (U.S. Bureau of Transportation Data)

This project uses **real-world U.S. airline delay data** to build a **machine learning model** that predicts whether a flight will be delayed or not. It demonstrates **data preprocessing**, **feature engineering**, and **classification modeling** using only Python.

---

## 📊 Problem Statement

Flight delays impact travelers, logistics, and the economy.  
Using data from the **U.S. Department of Transportation**, we built a system that predicts if a flight will be delayed based on key historical indicators.

---

## 📂 Dataset Overview

- 📁 File: `Airline_Delay_Cause.csv`
- 🏛 Source: [BTS.gov – Bureau of Transportation Statistics](https://www.transtats.bts.gov/)
- 📌 Data: Delay cause, flight stats, airport, carrier, date, month, etc.
- 🔢 Size: Thousands of rows, 30+ columns

---

## 🚀 Project Workflow

1. **Data Cleaning**  
   - Trimmed columns  
   - Handled missing values  
2. **Feature Engineering**  
   - Created target: `delay_status` (1 = delayed, 0 = on time)  
   - Converted categorical features  
3. **Modeling**  
   - Used `RandomForestClassifier`  
   - Evaluated using accuracy & classification report  
4. **Visualization**  
   - Feature importance chart  
   - Confusion matrix plot

---

## 🧠 Machine Learning Pipeline

| Stage               | Details                          |
|--------------------|----------------------------------|
| Target Variable     | `delay_status` (binary: 0/1)     |
| Features Used       | Year, Month, Carrier, Airport, etc. |
| Model               | `RandomForestClassifier`         |
| Evaluation          | Accuracy, Classification Report, Confusion Matrix |

---

## ✅ Results

- 🎯 **Accuracy:** ~85–90% (varies by subset)
- 📈 Important Features: `arr_cancelled`, `arr_diverted`, `carrier`, `airport`
- 🔍 Delays were more common with higher cancellations/diversions

---

## 📌 Technologies Used

- 🐍 Python
- 📊 Pandas, NumPy
- 🎨 Matplotlib, Seaborn
- 🤖 Scikit-learn
- 🧪 Google Colab (for development)

---

## 📉 Visual Outputs

> 🔹 Confusion Matrix  
> 🔹 Top Feature Importances  
> 🔹 Classification Report

---

## 📁 Project Structure

flight-delay-prediction/

├── Flight_Delay_Predictor.ipynb

├── Airline_Delay_Cause.csv

├── Download_Column_Definitions.csv

└── README.md


---

## 🌱 Future Improvements

- ✅ Deploy as a Streamlit web app
- ✅ Add time-series trends
- ✅ Integrate real-time data via FAA API
- ✅ Improve accuracy with XGBoost or LightGBM

---

## 🧠 What This Project Shows (To Recruiters)

- Real-world dataset from a government source  
- Business impact (flight delays = real money)  
- Clean ML workflow: cleaning → modeling → evaluation  
- Strong understanding of categorical encoding, feature importances  
- Fully Python-based — no external tools

---

## 🙌 Author & Contact

> **📧 [Abhijeet Roy]**  
> 💼 Aspiring Data Scientist | Python Enthusiast  
> 🌐 [You]  
> 🐙 GitHub: [Your GitHub]

---

## ⭐️ Like this project?

Star ⭐ the repo or fork it!  
Let’s connect and collaborate!

