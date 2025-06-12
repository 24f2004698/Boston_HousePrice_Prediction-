# Boston House Price Predictor

A simple, intuitive Flask app that estimates median house prices in Boston based on 13 key features. Plug in your numbers, hit “Predict,” and get an instant price estimate.

---

## 🚀 Live Demo

Check it out right here:  
👉 https://boston-houseprice-prediction-g32w.onrender.com/

---

## 🔧 Tech Stack

- **Backend**: Python · Flask  
- **Model**: Scikit-learn Linear Regression  
- **Frontend**: HTML · CSS (custom styles)  
- **Server**: Gunicorn (via Render)

---

## 📂 What’s Inside

```

Boston\_HousePrice\_Prediction-/
│
├── house\_price\_analysis.ipynb   # Notebook: data exploration → model training
├── house\_price\_analysis.pkl     # Saved Linear Regression model
├── app.py                       # Flask routes & prediction logic
├── requirements.txt             # All Python dependencies
├── templates/
│   └── index.html               # Input form + result display


````

---
MODEL IS TRAINED BASED ON DATA GIVEN IN THE REPO NAMED AS BostonHousing.cvs 
---

## 🔨 Quick Start (Local)

1. **Clone the repo**  
   ```bash
   git clone https://github.com/24f2004698/Boston_HousePrice_Prediction-.git
   cd Boston_HousePrice_Prediction-


2. **Create & activate a virtual environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate        # Windows: venv\Scripts\activate
   ```

3. **Install requirements**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app**

   ```bash
   python app.py
   ```

   Open your browser at `http://127.0.0.1:5000`




⚙️ How to Use

1. Enter values for all 13 Boston housing features (CRIM, ZN, INDUS, … LSTAT).
2. Click **Predict**.
3. See your price estimate appear below the form.


THANK YOU!!
