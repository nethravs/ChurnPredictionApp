# Customer Churn Prediction Application

## Demo
A demo video showcasing the working of the system along with project source files is included in the repository.

---

## About the Project

The Customer Churn Prediction Application is a Machine Learning-based web application built using Python and Streamlit.  
It predicts whether a customer will leave a service based on inputs such as age, gender, tenure, and monthly charges.

This helps businesses identify customers who are likely to churn and take preventive actions to improve retention.

---

## How the Project Works

### 1. User Input
The user enters customer details such as:
- Age  
- Gender  
- Tenure  
- Monthly Charges  

---

### 2. Data Preprocessing
- Gender is converted into numerical values:
  - Female → 1  
  - Male → 0  
- The input data is scaled using a pre-trained scaler (`scaler.pkl`) to match the training format.

---

### 3. Model Prediction
The processed input is passed into a trained machine learning model (`model.pkl`), which predicts:

- 1 → Customer will churn (Yes)  
- 0 → Customer will not churn (No)  

---

### 4. Output Display
The result is displayed instantly on the Streamlit web interface.

---

## Key Features

- Real-time churn prediction  
- Interactive Streamlit UI  
- Machine Learning-based classification  
- Data preprocessing using scaler  
- Instant prediction results  
- Lightweight and easy to run  

---

## Tools and Technologies Used

- Python  
- Streamlit  
- Scikit-learn  
- Pandas  
- NumPy  
- Joblib  
- Jupyter Notebook  

---

## Machine Learning Workflow

The project follows these steps:
- Data Collection  
- Data Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Model Training  
- Model Saving (`model.pkl`)  
- Scaler Saving (`scaler.pkl`)  
- Deployment using Streamlit  

---

## Input Features

- Age  
- Gender  
- Tenure  
- Monthly Charges  

---

## Prediction Logic

- 1 → Churn (Yes)  
- 0 → No Churn (No)  

---

## Applications

- Telecom customer retention  
- Banking customer analysis  
- Subscription-based businesses  
- Marketing strategy improvement  
- Customer behavior prediction  

---

## Challenges Faced

- Encoding categorical data correctly  
- Maintaining feature order during prediction  
- Scaling input consistently with training data  
- Integrating ML model with Streamlit  
- Debugging deployment issues  

---

## Conclusion

This project demonstrates how Machine Learning can be applied to solve real-world business problems like customer churn prediction.  
It helps companies identify at-risk customers and take proactive actions to improve retention.
