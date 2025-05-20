**AI-Powered Medical Diagnosis System**

An AI-driven web application designed to assist in early-stage disease prediction using Logistic Regression. This system allows users to input medical symptoms through a simple interface and returns predictive insights based on trained healthcare data. Built with Python and Streamlit, the tool offers a lightweight, fast, and accessible solution for diagnostic support.

Features :
- Disease Prediction using Logistic Regression
-  Data Preprocessing with feature selection and normalization
-  Streamlit Interface for easy symptom input and result display
-  Probability-based Output for confident decision support
-  Lightweight and fast – suitable for low-resource environments

Technologies Used
- Python
- Scikit-learn – for Logistic Regression and data modeling
- Pandas & NumPy – for data handling and preprocessing
- Streamlit – for building the interactive web app


How It Works :
DEMO --> ![image](https://github.com/user-attachments/assets/019212e9-06e7-46d5-b08e-74d41ab102e7)

- Select the Disease Type
The user begins by selecting a disease to predict from the dropdown menu. Available options include:
Diabetes
Heart Disease
Parkinson's Disease
Lung Cancer
Hypo-Thyroid

- Input Relevant Medical Data
After selecting the disease, the system dynamically displays the required input fields.

- Run Prediction
Once all input fields are filled, clicking the **Test Result** button will trigger the model to process the data.

- View Result Instantly
The result is displayed in real-time, such as:
**✅ The person is not diabetic** or **❌ The person is diabetic**, based on the model’s prediction.

This process is repeated for each disease type with its corresponding medical input fields and prediction logic.

