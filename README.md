# 📊 Medical Appointments No-Show Analysis  

## **Overview**
This project analyzes a dataset of **110,527** medical appointments to understand **factors affecting patient no-shows**. Using **exploratory data analysis (EDA)** and visualizations, we uncover patterns that influence whether patients attend their scheduled appointments.  

## **Dataset Description**
The dataset consists of medical appointments with key attributes such as **patient demographics, medical conditions, SMS reminders, and attendance records**.

### **Key Statistics**
📌 **Total Appointments:** **110,527**  
📌 **Average Patient Age:** **37.1 years** *(Min: -1, Max: 115)*  
📌 **Hypertension Cases:** **19.7%**  
📌 **Diabetes Cases:** **7.2%**  
📌 **Alcoholism Cases:** **3.04%**  
📌 **Patients Who Received SMS Reminders:** **32.1%**  
📌 **Scholarship Enrollment (Social Welfare Program):** **9.8%**  

## **Methodology**
### 🔹 Data Cleaning
- Removed anomalies (e.g., **invalid ages** such as -1).
- Converted date columns to `datetime` format.
- Extracted **weekday information** from `ScheduledDay` and `AppointmentDay`.

### 🔹 Exploratory Data Analysis (EDA)
- Visualized **attendance patterns** across different factors.
- Investigated the impact of **age, gender, medical conditions**, and **SMS reminders** on no-shows.
- Analyzed **time gaps** between scheduling and appointment date.

### 🔹 Key Insights
- **Older patients** are more likely to attend their appointments.
- **Longer wait times** between scheduling and appointment increase no-show rates.
- Patients receiving **SMS reminders** tend to attend more.
- Certain **neighborhoods** have higher no-show rates.

## **Technologies Used**
- **Python** (`pandas`, `numpy`) – Data manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive analysis  

## **Future Enhancements**
- Apply machine learning models to predict no-shows.
- Optimize SMS reminder strategy using predictive analytics.
- Perform geospatial analysis on no-show trends per neighborhood.
