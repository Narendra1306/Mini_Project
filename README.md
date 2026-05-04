# Mini_Project
Got it — here’s your updated **README.md** with your name included 👇

---

# 🏠 Multiple Linear Regression (MLR) using OOP in Python

## 📌 Project Overview

This project demonstrates the implementation of **Multiple Linear Regression (MLR)** using **Object-Oriented Programming (OOP)** concepts in Python.
The model predicts house prices based on multiple features such as bedrooms, bathrooms, area, location, etc.

---

## 🎯 Objectives

* Implement MLR using **scikit-learn**
* Apply **OOP concepts** for modular and reusable code
* Perform **data preprocessing**
* Train and evaluate the model
* Save and reload the trained model using **pickle**
* Predict results for custom input data

---

## 🛠️ Technologies Used

* Python 🐍
* NumPy
* Pandas
* Scikit-learn
* Pickle

---

## 📂 Project Structure

```
MLR_Project/
│
├── data.csv           # Dataset file
├── main.py            # Main Python script (MLR class)
├── Model.pkl          # Saved trained model
└── README.md          # Project documentation
```

---

## ⚙️ Features

* Data loading from CSV file
* Encoding categorical variables (`city`, `country`)
* Train-test split
* Model training using Linear Regression
* Model evaluation using:

  * R² Score
  * RMSE (Root Mean Squared Error)
* Custom prediction support
* Model saving & loading

---

## 🧠 OOP Concepts Used

* Class & Object
* Constructor (`__init__`)
* Encapsulation
* Method modularization
* Exception Handling

---

## 🔄 Workflow

1. Load dataset
2. Preprocess data (encoding categorical values)
3. Split dataset into training and testing sets
4. Train the model
5. Evaluate performance
6. Predict using custom input
7. Save and reload the model

---

## 📊 Model Evaluation Metrics

* **R² Score** → Measures accuracy
* **RMSE** → Measures prediction error

---

## ▶️ How to Run

```bash
# Install dependencies
pip install numpy pandas scikit-learn

# Run the program
python main.py
```

---

## 📈 Sample Output

```
Train Accuracy: 0.85
Train Loss: 12000

Test Accuracy: 0.82
Test Loss: 13500

Own point predictions: [450000]
Loaded model Predictions: 452000
```

---

## ⚠️ Notes

* Ensure `data.csv` is in the correct format
* Categorical encoding is basic (can be improved using One-Hot Encoding)
* Model performance depends on dataset quality

---

## 🚀 Future Improvements

* Use advanced encoding techniques
* Add feature scaling
* Deploy as a web application (Flask/Streamlit)
* Add visualization (Matplotlib/Seaborn)

---

## 👨‍💻 Author

**Muthireddy Narendra**

---

If you want, I can also:

* Add your **college name + project guide**
* Make it **more attractive with badges & GitHub styling**
* Or convert this into **PPT/report format** 👍
