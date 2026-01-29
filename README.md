# 🏆 HR Performance Awards – NumPy & Pandas Mini Project

This project demonstrates the use of **NumPy and Pandas** to analyze employee performance metrics and identify top performers for **monthly RnR (Rewards & Recognition)**—inspired by **Amazon-style performance evaluation metrics**.

It is designed as an **industry-oriented Python mini project** for data analysis beginners and AIML students.

---

## 📌 Project Objective

To analyze employee performance based on:
- **Accuracy**
- **Productivity**
- **Velocity**

…and identify **award-worthy employees** using statistical analysis, feature engineering, and ranking logic.

---

## 📊 Metrics Used

| Metric | Description |
|------|------------|
| Accuracy | Quality of work (%) |
| Productivity | Output efficiency (score out of 100) |
| Velocity | Task completion speed (scaled tasks/hour) |

---

## 🛠️ Technologies Used

- **Python**
- **NumPy** – numerical computations
- **Pandas** – data manipulation & analysis

---

## 🗂️ Project Structure


HR-Performance-Awards/
│
├── hr_performance_awards.py   # Main Python script
├── README.md                  # Project documentation

## Key Features
1️⃣ Employee Dataset Creation

Created a structured employee dataset using Pandas DataFrame.

2️⃣ Data Inspection

Previewed data using:

.head()

.info()

3️⃣ NumPy Statistical Analysis

Converted DataFrame columns to NumPy arrays.

Calculated:

Mean Accuracy

Max Productivity

Min Velocity

4️⃣ Feature Engineering

Created new metrics:

TotalScore

AverageScore

TotalScore = Accuracy + Productivity + Velocity

5️⃣ Award Eligibility Logic

Employees with TotalScore > 250 are shortlisted for awards.

6️⃣ Ranking & Winner Selection

Ranked employees based on TotalScore.

Identified Top Performer of the Month.

🏅 Sample Output

📈 Ranked employees from highest to lowest score

🥇 Monthly Award Winner

🎯 List of award-eligible employees

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/HR-Performance-Awards.git


Navigate to the project folder:

cd HR-Performance-Awards


Run the script:

python hr_performance_awards.py

🚀 Learning Outcomes

Practical use of NumPy arrays

Hands-on Pandas DataFrame operations

Feature engineering fundamentals

Real-world HR analytics use case

Clean, readable Python project structure

📌 Future Enhancements

Weighted scoring for metrics

Monthly & yearly performance trends

Data visualization using Matplotlib / Seaborn

Export reports to CSV or Excel

Convert into a Machine Learning performance predictor
---


## 👨‍💻 Author

**Mohammed Anam Ullah**
AIML Student | Python | Data Analysis

## 📧 Email: anaamkhan49@gmail.com

📍 Hyderabad, Indi
