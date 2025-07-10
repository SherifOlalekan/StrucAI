# 🏗️ StrucAI – AI-Powered Structural Risk Predictor

StrucAI is an intelligent web app that uses machine learning to predict the **structural risk level** of buildings or infrastructure — based on simulated sensor data. It helps engineers, inspectors, and urban planners make **data-driven decisions** faster and smarter.

---

## 💡 Problem Statement

Many developing regions face challenges with **timely structural inspections**, leading to overlooked wear, cracks, and strain — and ultimately, **structural failures**. Traditional inspections are manual, slow, and expensive.

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

> Coming soon — video walkthrough and screenshots

---

## 📁 Project Structure

```
StrucAI/
│
├── strucai_app.py                   # Main Streamlit app
├── strucai_model.pkl                # Trained ML model
├── strucai_scaler.pkl               # Scaler used in preprocessing
├── sample_data.csv                  # Sample sensor dataset for demo
├── strucai_app_with_monthly_peaks.py # Extended app with peak trends
└── README.md                        # You're here!
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
   streamlit run strucai_app_with_monthly_peaks.py
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

## ❤️ Made With

- Python 🐍
- Streamlit ⚡
- Scikit-learn 🤖
- The #3MTT Program by @NITDANigeria

---

## 🙏 Acknowledgements

This project was built by **Sherif Olalekan Akeem** during the 3MTT Data & AI program.  
Thanks to @3mttNigeria, @bosuntijani, @IHSTowers, and @NITDANigeria for powering the journey.

---

## 🔗 Connect

- [LinkedIn](https://www.linkedin.com/in/yourprofile)
- [Twitter](https://twitter.com/yourhandle)
- [YouTube Demo](https://youtu.be/your-video-link) (if available)

---

> “Built with ❤️ at the intersection of civil engineering and artificial intelligence.”
