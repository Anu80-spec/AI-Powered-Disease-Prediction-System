# 🏥 HealthBridge AI — My Capstone-Style AI Web Project

Hi! I'm Anushree Bhargava 👋  
This is one of the most exciting and challenging projects I’ve worked on — a web-based medical assistant powered by AI.
HealthBridge predicts possible diseases based on user symptoms and gives nearby hospital suggestions. 
I wanted to build something meaningful, practical, and technical — this is my take on combining AI + real-world utility.

---

## ✨ Why I Built This

- I’ve always been curious about how AI can help in real life — especially in healthcare.
- I wanted to build something that’s not just a form project, but **does something real**.
- This app helps users figure out what might be wrong (based on symptoms) and **instantly shows nearby hospitals** using maps.

---

## 🚀 What It Can Do

- Predict likely **diseases** based on multiple symptoms
- Suggest **medication** and **precautions**
- Show **hospitals near you** on a real map (OpenStreetMap)
- If it detects **critical symptoms**, it flashes an **emergency alert**
- All built using **Python (Flask)** and **AI models**

---

## 🔧 Tech & Tools I Used

- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Python + Flask
- **Machine Learning**: 
  - `pandas`, `scikit-learn','numpy'
  - I used a symptom-disease dataset and trained a classifier
- **Mapping**: 
  - OpenStreetMap + Leaflet.js (for showing hospitals)
  - Geolocation API

---

## 📸 Glimpses of the App

| 💡 Disease Prediction | 🏥 Hospital Suggestions |
|----------------------|-------------------------|
| ![Disease Prediction](screenshots/disease-prediction.png) | ![Hospital Map](screenshots/hospital-map.png) |

---

## 🔄 How to Run It

If you want to try it locally:

```bash
git clone https://github.com/Anu80-spec/AI-Powered-Disease-Prediction-System.git
cd AI-Powered-Disease-Prediction-System
pip install -r requirements.txt
python app.py
