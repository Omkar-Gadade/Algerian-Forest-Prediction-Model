

# 🔥 Regression Prediction Model – Algerian Forest Fires

This project focuses on predicting the **Fine Fuel Moisture Code (FFMC)** index from the **Algerian Forest Fires Dataset** using various **Linear Regression** models and regularization techniques. It also includes deployment via a Flask web application.

---

## 📊 Dataset

The **Algerian Forest Fires Dataset** contains **244 instances** from two regions of Algeria: **Bejaia** and **Sidi Bel-abbes**. Each region has 122 records collected between **June and September 2012**.

### 📌 Features

* **Date**: DD/MM/YYYY
* **Temp**: Temperature at noon (22°C to 42°C)
* **RH**: Relative Humidity (21% to 90%)
* **WS**: Wind Speed (6 to 29 km/h)
* **Rain**: Daily Rainfall (0 to 16.8 mm)
* **DMC, DC, ISI, BUI, FWI**: Fire Weather Index components
* **Target Variable**: **FFMC** (Fine Fuel Moisture Code)
* **Class**: Fire / Not Fire

---

## 🔧 Project Workflow

1. **Data Preprocessing**

   * Splitting the dataset into training and testing sets
   * Handling multicollinearity
   * Feature scaling and analysis

2. **Exploratory Data Analysis**

   * Visualizations using **Matplotlib** and **Seaborn**

3. **Modeling**

   * Linear Regression
   * Lasso Regression (L1 Regularization)
   * Ridge Regression (L2 Regularization)
   * Elastic Net Regression
   * Cross-validation for model evaluation

4. **Model Serialization**

   * Pickling trained models for later use

5. **Web Deployment**

   * Flask app with `app.py`
   * HTML template (`home.html`) for UI
   * Web interface for user input and FFMC prediction

---

## 🛠 Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Flask
* Pickle

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/forest-fire-ffmc-regression.git
   cd forest-fire-ffmc-regression
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask app:

   ```bash
   python application.py run
   ```

4. Open your browser and go to `http://127.0.0.1:5000/`

---

## 🌐 Web App Features

* Interactive form to enter feature values
* Real-time prediction of FFMC index
* Clean and simple HTML interface

---


## 📌 Acknowledgment

Dataset source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/datasets/?search=Algerian+Forest+Fires)

---

Would you like me to generate a `requirements.txt` file or help with a GitHub-ready project structure?
