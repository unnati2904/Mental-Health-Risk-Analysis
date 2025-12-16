# Mental Health Risk Analysis System

## 📌 Project Overview
This project analyzes behavioral survey data to identify mental health risk levels using Python and NumPy. 
It focuses on awareness-based risk analysis rather than medical diagnosis.

## 🎯 Objective
To calculate a mental health risk score using normalized behavioral factors and classify users into Low, Medium, or High risk categories.

## 📊 Dataset Description
The dataset is represented as a NumPy 2D array where:
- Rows represent users
- Columns represent behavioral factors

### Behavioral Factors
1. Sleep (hours per day)
2. Screen Time (hours per day)
3. Workload (scale 1–10)
4. Mood (scale 1–10)
5. Exercise (hours per week)

## ⚙️ Technologies Used
- Python
- NumPy

## 🧠 Methodology
1. Created a structured NumPy dataset (users × factors)
2. Applied Min–Max normalization to scale features between 0 and 1
3. Assigned weights to each behavioral factor based on impact
4. Calculated weighted mental health risk scores using NumPy dot product
5. Classified risk levels using threshold-based logic

## 📈 Output
Each user is assigned:
- A numerical risk score
- A corresponding risk category (Low / Medium / High)

## ⚠️ Ethical Disclaimer
This project is intended for mental health awareness and analytical purposes only and should not be considered a medical or clinical diagnosis.

