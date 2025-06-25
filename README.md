# 💤 Sleep Disorder Prediction 🧠🌙

This project focuses on predicting the likelihood of sleep disorders using personal, physiological, and lifestyle attributes. models like **Decision Tree** 🌳 and **Random Forest** 🌲 were applied to analyze and classify potential sleep-related issues.

---

## 📌 **Project Overview**

🔍 **Objective**:
- Perform **Exploratory Data Analysis (EDA)** on health and sleep-related data.
- Build and evaluate **classification models** to predict sleep disorders.
- Compare **Decision Tree** and **Random Forest** performance.
- Visualize health patterns affecting **sleep quality** and **disorder prevalence**.

---

## 🗂️ **Dataset Information**

| Feature                  | Description                                      |
|--------------------------|--------------------------------------------------|
| Person ID                | Unique identifier for each individual            |
| Gender                   | Gender of the person (Categorical)               |
| Age                      | Age in years (Numeric)                           |
| Occupation               | Job type (Categorical)                           |
| Sleep Duration           | Average sleep in hours (Numeric)                 |
| Quality of Sleep         | Self-reported sleep quality score (1–10)         |
| Physical Activity Level  | Daily physical activity level (1–10)             |
| Stress Level             | Self-reported stress level (1–10)                |
| BMI Category             | Body Mass Index category (Categorical)           |
| Blood Pressure           | Systolic/Diastolic blood pressure (String)       |
| Heart Rate               | Resting heart rate (Numeric)                     |
| Daily Steps              | Average daily steps (Numeric)                    |
| Sleep Disorder           | Target class label (None, Insomnia, Apnea, etc.) |

---

## 🛠️ **Technologies Used**

- **Python 3.12+**
- **Pandas** 🐼
- **NumPy** 🔢
- **Scikit-learn** 🤖
- **Matplotlib & Seaborn** 📊
- **Jupyter Notebook** 📓

---

## 🔎 **Project Workflow**

1. **Data Preprocessing** 🧹  
   - Dropped unnecessary columns (e.g., `Person ID`).
   - Filled missing values and encoded categorical features.
   - Split `Blood Pressure` into systolic/diastolic values.

2. **Exploratory Data Analysis (EDA)** 📈  
   - Analyzed the effect of stress, activity, and heart rate on sleep disorders.
   - Visualized distributions and correlations among variables.

3. **Model Building** 🤖  
   - Applied **Decision Tree Classifier** 🌳.
   - Applied **Random Forest Classifier** 🌲.

4. **Model Evaluation** ⚖️  
   - Compared using **Accuracy**, **Precision**, **Recall**, and **F1 Score**.
   - Visualized Actual vs Predicted results.

5. **Key Insights** 🔍  
   - High stress, poor sleep quality, and low activity often indicate sleep disorders.
   - Random Forest showed better accuracy and generalization.

---

> ✅ **Random Forest Classifier achieved higher accuracy and better prediction results than Decision Tree.**

---

## 💻 Author

- Naveen Kumar S – [Contect Me](https://github.com/naveenkumar279)  
- Passionate about Python, Data Analysis & HealthTech 🌱
