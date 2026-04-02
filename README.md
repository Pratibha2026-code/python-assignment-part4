# python-assignment-part4
# 📊 Student Performance Analysis & Prediction

This project analyzes student performance data, creates visualizations, and builds a machine learning model to predict whether a student will pass or fail.

---

## 📌 Objective

The goal of this project is to:

* Explore and understand student data
* Visualize patterns using graphs
* Build a prediction model using machine learning

---

## 📁 Dataset

The dataset contains information about 15 students:

* Subject scores: Math, Science, English, History, PE
* Attendance percentage
* Study hours per day
* Pass/Fail status (1 = Pass, 0 = Fail)

---

## 🔍 Task 1 — Data Exploration (Pandas)

* Loaded dataset using pandas
* Displayed first 5 rows using `.head()`
* Checked dataset shape and data types
* Generated summary statistics using `.describe()`
* Counted number of students who passed and failed
* Calculated average subject scores for:

  * Passing students
  * Failing students
* Identified the top-performing student based on average score

---

## 📊 Task 2 — Data Visualization (Matplotlib)

Created and saved the following plots:

* 📊 Bar Chart — Average score per subject
* 📉 Histogram — Distribution of math scores (with mean line)
* 📍 Scatter Plot — Study hours vs average score (Pass vs Fail)
* 📦 Box Plot — Attendance comparison (Pass vs Fail)
* 📈 Line Plot — Math vs Science scores for all students

---

## 🎨 Task 3 — Data Visualization (Seaborn)

* Created bar plots comparing:

  * Math scores (Pass vs Fail)
  * Science scores (Pass vs Fail)
* Created scatter plot:

  * Attendance vs Average Score
  * Colored by Pass/Fail
  * Added regression lines

### 🧠 Comparison:

* Seaborn is easier and more visually appealing
* Matplotlib provides more control but requires more code

---

## 🤖 Task 4 — Machine Learning (scikit-learn)

### 🔹 Model Used:

* Logistic Regression

### 🔹 Steps:

* Selected features and target variable
* Split data into training and testing sets (80/20)
* Scaled features using StandardScaler
* Trained the model on training data

### 🔹 Results:

* Printed training accuracy
* Printed test accuracy
* Displayed predictions for test students with correctness check

---

## 📊 Feature Importance

* Extracted model coefficients
* Sorted features by importance
* Visualized using horizontal bar chart
* Interpreted:

  * Positive values → increase chances of passing
  * Negative values → increase chances of failing

---

## 🔮 Bonus — New Student Prediction

* Predicted Pass/Fail for a new student
* Displayed prediction probability

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🚀 Key Learning Outcomes

* Data analysis using pandas
* Data visualization using Matplotlib and Seaborn
* Machine learning workflow (train, test, predict)
* Feature importance interpretation

---

## 📌 Conclusion

This project demonstrates a complete data science workflow:

* Data exploration
* Data visualization
* Machine learning prediction

Due to the small dataset, accuracy may vary, but the focus is on understanding the process end-to-end.

---

## 👩‍💻 Author

Pratibha Rathore
