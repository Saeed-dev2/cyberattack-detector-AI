# 🔐 cyberattack-detector-AI

A FastAPI-based AI web application for real-time **cyberattack detection** using a trained machine learning model. It provides an interactive web interface for users to input network traffic features and receive live predictions on whether the traffic is **Benign** or an **Attack**.

---
## 🚀 Features

- ✅ Built with **FastAPI** for high-speed performance
- 🔍 Predicts attacks using a trained **scikit-learn** model
- 📈 Uses a **StandardScaler** for input feature normalization
- 🧠 Dynamic input form generated from `features.pkl`
- 💡 User-friendly web interface with **Jinja2 templates**
- 🧪 Robust error handling and form validation

---

## 📁 Project Structure

```
cyberattack-detector-AI/
│
├── main.py               # FastAPI backend
├── model.pkl             # Trained ML model
├── scaler.pkl            # Fitted StandardScaler
├── features.pkl          # List of input features
├── templates/
│   └── index.html        # Web form and result display
├── static/               # CSS or image assets (optional)
└── README.md             # This file
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/cyberattack-detector-AI.git
   cd cyberattack-detector-AI
   ```

2. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   uvicorn main:app --reload
   ```

4. **Access the app**
   Open your browser and go to:  
   👉 `http://127.0.0.1:8000`

---

## 📊 How It Works

1. Loads the ML model, scaler, and feature list.
2. Renders a form with all required feature fields.
3. On form submission:
   - Values are collected and scaled.
   - The model makes a prediction.
   - The result is displayed as **Benign** or **Attack**.

---

## ✅ Requirements

- Python 3.8+
- FastAPI
- Uvicorn
- scikit-learn
- joblib
- Jinja2

Install all requirements:
```bash
pip install fastapi uvicorn scikit-learn joblib jinja2
```

---

## 📷 Screenshot

> *(Add your UI screenshot here once available)*  
> Example:
> ![App Screenshot](static/screenshot.png)

---

## 📜 License

This project is licensed under the **MIT License** 

---

## 👨‍💻 Author

**Muhammad Saeed**  
AI & Machine Learning & IoT Enthusiast  
