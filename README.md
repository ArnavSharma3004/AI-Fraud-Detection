# Insurance Fraud Detection Using Machine Learning

## 📌 Overview
An end-to-end AI-powered system that automatically detects 
fraudulent insurance claims using supervised machine learning. 
The system processes historical claims data, trains multiple 
ML classifiers, and serves real-time fraud predictions through 
a Flask web dashboard deployed via ngrok.

## 🚨 Problem Statement
Insurance companies lose billions annually due to fraudulent 
claims. Manual review is slow, inconsistent, and unable to 
detect complex fraud patterns at scale. This system automates 
fraud detection with data-driven ML predictions.

## ✅ Solution
A complete ML pipeline that:
- Ingests and preprocesses insurance claims data
- Performs exploratory data analysis (EDA)
- Trains and evaluates 4 ML classifiers
- Serves real-time fraud predictions via Flask API
- Deployed publicly using ngrok

## 🛠️ Tech Stack
- **Language:** Python 3.9+
- **ML Library:** Scikit-learn
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Web Framework:** Flask
- **Deployment:** ngrok
- **Environment:** Google Colab / Jupyter Notebook

## 🤖 Models Used
| Model | Accuracy | F1-Score |
|-------|----------|----------|
| Decision Tree | ~78% | ~0.73 |
| Random Forest | ~84% | ~0.85 |
| KNN | ~76% | ~0.71 |
| Gradient Boosting | ~82% | ~0.80 |

✅ **Random Forest selected as primary model**

## 📂 Project Structure
```
AI-Fraud-Detection/
│
├── smart_bridge_ai_updated.ipynb  # Main notebook
├── insurance_claims.csv           # Dataset
├── std_scaler.pkl                 # Saved scaler
├── model.pkl                      # Saved ML model
├── requirements.txt               # Dependencies
└── README.md                      # Documentation
```

## ⚙️ How to Run
1. Clone the repository
```
   git clone https://github.com/ArnavSharma3004/AI-Fraud-Detection.git
```
2. Install dependencies
```
   pip install -r requirements.txt
```
3. Open `smart_bridge_ai_updated.ipynb` in Google Colab
4. Run all cells
5. Access the app via the ngrok URL generated in the last cell

## 📊 Dataset
- **File:** insurance_claims.csv
- **Records:** 1,000 claims
- **Features:** 40 columns including age, policy_annual_premium, 
  incident_severity, fraud_reported (target)

## 🔮 Future Enhancements
- SHAP explainability for per-claim predictions
- Real-time streaming with Flask-SocketIO
- Automated model retraining pipeline
- Mobile app integration
- Permanent cloud deployment

## 👥 Team
- **Team ID:** SmartBridge-AI-01
- **Project:** Insurance Fraud Detection Using Machine Learning
- **Platform:** SmartBridge / IBM SkillsBuild

## 📄 License
This project is for educational purposes under the 
SmartBridge AI internship program.
