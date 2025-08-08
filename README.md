# 🏗️ StrucAI – AI-Powered Structural Risk Predictor

StrucAI is an intelligent web app that uses machine learning to predict the **structural risk level** of buildings or infrastructure, based on simulated sensor data. It helps engineers, inspectors, and urban planners make **data-driven decisions** faster and smarter.

---

## 💡 Problem Statement

Many developing regions face challenges with **timely structural inspections**, leading to overlooked wear, cracks, and strain, and ultimately, **structural failures**. Traditional inspections are manual, slow, and expensive.

---

## 🚀 Solution

StrucAI provides a **lightweight AI tool** that accepts key structural sensor inputs and instantly classifies the **risk level** of a structure as:

- ✅ Low Risk
- ⚠️ Medium Risk
- 🚨 High Risk

It also displays the **confidence level** of the AI prediction and visualizes **monthly peak trends** if historical data is uploaded.

---

## 🧠 Key Features

- 🔍 Predict structural risk from:
  - Vibration (Hz)
  - Strain (µε)
  - Temperature (°C)
  - Crack Width (mm)
  - Structural Age (years)
- 📊 Upload CSVs to see **monthly peak trends** per feature
- 🧠 Trained on 10,000+ rows of synthetic data using **Random Forest**
- 🎛️ Built with **Python, Streamlit, Pandas, Scikit-learn**
- 🌐 No coding required to use the app

---

## 🖼️ Demo Preview

<img width="976" height="600" alt="image" src="https://github.com/user-attachments/assets/618c43bb-85ce-4a38-895d-81e87f346191" />


---

## 📁 Project Structure

```
StrucAI/
│
├── strucai_app.py
├── strucai_label_encoder.pkl
├── strucai_rf_model.pkl
├── strucai_simulated_data_10k.csv
├── requirements.txt
└── README.md
```

---

## ⚙️ How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/strucai.git
   cd strucai
   ```

2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate    # or venv\Scripts\activate on Windows
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run strucai_app.py
   ```

---

## 📌 Requirements

- Python 3.8+
- Streamlit
- Pandas
- Scikit-learn
- Matplotlib (for optional plots)

---

## 📊 Simulated Data Info

The model was trained on 10,000 rows of synthetic structural sensor data, with features engineered to reflect real-world ranges for cracks, vibration, temperature, and structural stress.

---

## Made With

- Python 🐍
- Streamlit ⚡
- Scikit-learn 🤖
---


> “Built with ❤️ at the intersection of civil engineering and artificial intelligence.”
