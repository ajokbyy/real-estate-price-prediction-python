# 🏠 Real Estate Price Prediction

A machine learning web application that predicts the price of houses in Bangalore based on location, square footage, number of bedrooms, and other parameters.  
The project combines **data preprocessing**, **model training**, and **full-stack integration** to deliver predictions via a user-friendly web interface.

---

## 📌 Features
- Predicts house prices in Bangalore with **92% accuracy**.
- Interactive web UI built with **HTML, CSS, and JavaScript**.
- **Flask API** to serve the trained ML model.
- End-to-end pipeline from **dataset preprocessing** to **model deployment**.
- Modular and scalable codebase for easy enhancements.

---

## 🛠 Tech Stack
**Frontend:** HTML, CSS, JavaScript  
**Backend:** Python (Flask)  
**Machine Learning:** Scikit-learn, Pandas, NumPy  
**Dataset:** Bangalore Home Prices Dataset (Kaggle)  
**Other Tools:** Jupyter Notebook, Pickle

---

## 📂 Project Structure
```
real-estate-price-prediction/
│
├── data/
│   └── bangalore_home_prices.csv      # Raw dataset
├── model/
│   ├── model_training.ipynb           # Model training notebook
│   └── real_estate_model.pkl          # Saved ML model
├── app/
│   ├── app.py                         # Flask backend
│   ├── templates/
│   │   └── index.html                 # Frontend HTML
│   ├── static/
│   │   ├── style.css                  # Styling
│   │   └── script.js                  # Client-side logic
├── requirements.txt                   # Dependencies
└── README.md                          # Project documentation
```

---

## ⚙️ Installation & Setup

### **1. Clone the Repository**
```bash
git clone https://github.com/<your-username>/real-estate-price-prediction.git
cd real-estate-price-prediction
```

### **2. Create a Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate    # For Mac/Linux
venv\Scripts\activate       # For Windows
```

### **3. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4. Run the Application**
```bash
python app/app.py
```
The app will be available at **http://127.0.0.1:5000/**

---

## 📊 How It Works
1. **Data Preprocessing**
   - Cleaned the dataset by removing outliers and handling missing values.
   - Applied one-hot encoding for categorical variables like location.
   - Normalized numerical features for better model performance.

2. **Model Training**
   - Used **Linear Regression** for predicting prices.
   - Achieved **92% accuracy** on test data.
   - Saved the trained model using **Pickle**.

3. **Backend Integration**
   - Flask API loads the trained model once and serves predictions for incoming requests.

4. **Frontend**
   - Simple and responsive UI for user input.
   - JavaScript sends input data to Flask API and displays predictions instantly.

---

## 📈 Performance Optimization
- Cached the ML model in memory after initial load.
- Optimized preprocessing pipeline for faster predictions.
- Modularized code for scalability and maintainability.

---

## 📷 Demo Screenshots
*(Add images of your app UI and prediction output here)*

---

## 📄 License
This project is licensed under the MIT License — you are free to use and modify it.

---

## 👤 Author
**Abhiraj Singh Chouhan**  
[LinkedIn](https://www.linkedin.com/in/abhirajsinghchouhan/) | [GitHub](https://github.com/ajokbyy)
