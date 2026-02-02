# 🎓 Student Performance Prediction Using Machine Learning

##  Project Overview
This project aims to predict **student academic performance** using multiple **Machine Learning algorithms**.  
By training different models on student-related data, we evaluate and compare their performance using
standard metrics to identify the most effective algorithm.

The project focuses on both:
- **Regression** (predicting marks/scores)
- **Classification** (predicting Pass/Fail outcomes)

---

##  Objectives
- Understand the student performance dataset  
- Clean and preprocess raw data  
- Apply multiple Machine Learning algorithms  
- Evaluate and compare model performance  
- Select the best-performing model for prediction  

---

##  Machine Learning Algorithms Used

### 1️⃣ Linear Regression
- Used for **predicting continuous numerical values**
- Assumes a linear relationship between input features and output
- Suitable for predicting **exam scores or marks**

### 2️⃣ Logistic Regression
- Used for **binary classification problems**
- Output is categorical (e.g., Pass / Fail)
- Uses the **Sigmoid function** to map predictions between 0 and 1

### 3️⃣ Random Forest Regression
- An **ensemble learning** algorithm
- Combines predictions from multiple decision trees
- Helps reduce overfitting and improves prediction accuracy

---

##  Technologies & Libraries Used
- **Python** – Core programming language  
- **NumPy** – Numerical computations  
- **Pandas** – Data manipulation and analysis  
- **Matplotlib / Seaborn** – Data visualization  
- **Scikit-learn** – Machine Learning models and utilities  
- **Jupyter Notebook** – Interactive development environment  

---

##  Project Workflow
The complete workflow followed in this project is shown below:

```
Data Collection
      ↓
Data Cleaning & Preprocessing
      ↓
Feature Selection
      ↓
Train–Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Result Comparison
```

### Workflow Explanation
- **Data Collection**: Load the student dataset  
- **Data Cleaning & Preprocessing**: Handle missing values and encode categorical data  
- **Feature Selection**: Select important input variables  
- **Train–Test Split**: Split data into training and testing sets  
- **Model Training**: Train ML models using training data  
- **Model Evaluation**: Evaluate models using test data  
- **Result Comparison**: Compare performance metrics  

---

##  Evaluation Metrics
The following metrics are used to evaluate model performance:
- **Mean Absolute Error (MAE)** – Average absolute prediction error  
- **Mean Squared Error (MSE)** – Penalizes larger errors  
- **R² Score** – Measures goodness of fit  
- **Accuracy** – Used for Logistic Regression classification  

---

##  Results
- **Random Forest Regression** provides better accuracy compared to Linear Regression  
- **Logistic Regression** performs well for Pass/Fail classification  
- Comparing multiple models helps in selecting the most suitable algorithm  

---

##  Conclusion
This project demonstrates how different Machine Learning algorithms can be applied to
student performance prediction and highlights the importance of model comparison
for achieving better accuracy and reliability.
