# 📊 Credit Risk Modelling Web App

This is a machine learning-powered web application that predicts the **credit risk** (probability of default), assigns a **credit score**, and rates the creditworthiness of a loan applicant based on various financial and behavioral metrics.

🚀 Built using **Python**, **scikit-learn**, **XGBoost**, and deployed with **Streamlit Cloud**.

---

## 🔍 Features

- Predicts **default probability** for loan applicants.
- Calculates a **credit score** (range: 300 to 900).
- Assigns a **rating**: Poor, Average, Good, or Excellent.
- Clean, interactive **Streamlit UI**.
- Simple dropdowns and number inputs for ease of use.

---

## 📦 Technologies Used

- Python
- Pandas, NumPy
- scikit-learn
- XGBoost
- joblib
- Streamlit

---

## 🧠 Machine Learning

- Model trained on structured credit data with features such as:
  - Age, Income, Loan Amount
  - Credit Utilization Ratio
  - Delinquency Metrics
  - Residence & Loan Types
- Feature engineering and scaling using **MinMaxScaler**.
- Model and scaler saved using `joblib` for deployment.

---

## 📁 Project Structure

```
ml-project-credit_risk_model/
│
├── app/
│   ├── main1.py                # Streamlit app
│   └── prediction_helper1.py   # Model loading & prediction logic
│
├── artifacts/
│   └── model_data.joblib       # Trained model + scaler + metadata
│
├── requirements.txt            # All dependencies
└── README.md                   # You're here!
```

---

## ⚙️ How to Run Locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/Ayush95697/ml-project-credit_risk_model.git
   cd ml-project-credit_risk_model
   ```

2. **Create virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # on Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app**
   ```bash
   streamlit run app/main1.py
   ```

---

## 🌐 Live Demo

👉 [Check out the deployed app here](https://ayush95697-ml-project-credit-risk-model-main1-xyz.streamlit.app)

---

## 🙌 Credits

- Project guided by Codebasics ML course
- Developed by **Ayush Mishra**
- Special thanks to the open-source Python community ❤️

---

## 📬 Contact

Feel free to reach out:

- 📧 [ayushmishra7548@gmail.com](mailto:ayushmishra7548@gmail.com)
- 📱 +91 9569776503
- 💼 [LinkedIn Profile](https://www.linkedin.com/in/ayushmishra-portfolio)

---

## 📌 License

This project is for educational purposes only.
