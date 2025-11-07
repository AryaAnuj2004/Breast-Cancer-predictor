# Breast-Cancer-Predictor
## Introduction
This project is a small web app that predicts whether a breast cell cluster is benign or malignant using a trained machine learning model. You enter the cytology measurements through sliders, and the app shows the predicted result along with the probability score. It also generates a radar chart so you can compare the mean, standard error, and worst values of the cell features.

---

## ✨ Features
- Manually enter cytology measurement values
- Displays prediction: Benign or Malignant
- Shows probability for each class
- Radar chart visualization of important cell features
- Clean and simple UI (built using Streamlit)

---

## 🛠️ Tech used
- Python
- Streamlit
- Plotly (for radar chart)
- Scikit-learn (for model training)
- Pickle (for loading the saved model and scaler)

---

## Project structure

          |-- main.py
          |-- model/
          |   |-- main.py
          |   |-- model.pkl
          |   |-- scaler.pkl
          |-- assets/
          |   |-- style.css
          |-- data/
          |   |-- data.csv

---

## 🚀 How to run this project
1. Clone the repository:
  ```
  git clone https://github.com/AryaAnuj2004/Breast-Cancer-Predictor
  ```

2. Install required dependencies:

  ```
  pip install -r requirements.txt
  ```

3. Run the Streamlit app:

  ```
  streamlit run main.py
  ```

4. A browser tab will open with the app.

---

## 🧠 How it works
- User enters feature values in the sidebar.
- The input values are scaled using the trained scaler.
- The model predicts the cell cluster type.
- A radar chart shows how the input compares across different feature categories.

---

## ⚠️ Disclaimer

  #### This project is only for educational and demonstration purposes. It cannot replace a medical or professional diagnosis.

---

## 📎Demo Link

  ```
  https://breast-cancer-predictor-by-anuj-arya.streamlit.app/
  ```
---



