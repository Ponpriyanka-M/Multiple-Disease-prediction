# Multiple-Disease-prediction
This project explains how the analysis makes and predict the patient have disease or not...

# 🩺 Multiple Disease Prediction System

## 👋 Overview

This project is a **Streamlit web application** that predicts the presence of **Kidney Disease**, **Liver Disease**, and **Parkinson's Disease** using pre-trained machine learning models. It allows users to enter patient data, receive prediction results instantly, and encourages early medical consultation.

---

## 🎯 Objective

- Detect diseases early through machine learning-based models.
- Support clinical decision-making by providing fast predictions.
- Reduce diagnosis time and encourage preventive healthcare.
- Can download report of patient.

---

## 🏥 Diseases Covered

- 🧫 **Kidney Disease** – Includes chronic kidney conditions and indicators.
- 🧬 **Liver Disease** – Detects liver functionality based on bilirubin, enzymes, and proteins.
- 🧠 **Parkinson’s Disease** – Uses speech-related parameters to detect symptoms.

---

## 🖥️ App Features

- User-friendly sidebar menu to switch between disease pages.
- Input forms for patient name, age, and clinical parameters.
- Visual home page with disease-specific information and icons.
- Customized background styling and responsive layout.
- Health messages tailored to diagnosis results.
- Backend models loaded from `.sav` files using `pickle`.

---

## 🛠️ Technologies Used

- **Python 3**
- **Streamlit** – Web interface
- **Scikit-learn** – Model training and loading
- **Pandas & NumPy** – Data processing
- **Pickle** – Model serialization
- **Requests** – For fetching online images
- **HTML/CSS in Streamlit** – For custom styling

---

## 🚀 How to Run

1. Clone this repository or download the files.
2. Make sure all required `.sav` model files are in place.
3. Install dependencies:
   ```bash
   pip install streamlit pandas scikit-learn pillow requests
   ```
4. Run the Streamlit app:
   ```bash
   streamlit run streamlit1.py
   ```

---

## 🧪 Sample Screens

- Home page: summary and visuals for all disease modules
- ![image](https://github.com/user-attachments/assets/c2ae72fb-02f2-4d4d-bde3-8277f48fedf5)

- Kidney, Liver, Parkinson's prediction forms with custom messages
- ![image](https://github.com/user-attachments/assets/f61d29f4-8442-4d3d-993b-688a8160c4be)
- ![image](https://github.com/user-attachments/assets/7a36fb49-4927-4b04-aafa-f47a955c012e)
- ![image](https://github.com/user-attachments/assets/b0f448a9-daf7-4c8c-983b-f51a62f3ebeb)




---

## 🤝 Contribution

Feel free to improve UI, add new disease modules, or contribute performance enhancements.

---

