# Bank Customer Churn Prediction

This project predicts whether a bank customer will exit (churn) or stay with the bank using Machine Learning models.  
The goal is to help banks identify at-risk customers early and take proactive retention measures.

---

## Project Overview
Customer churn (attrition) refers to when customers stop using a company’s services.  
In banking, customer retention is critical as acquiring new customers costs much more than retaining existing ones.  

This project uses classification algorithms to predict churn based on customer features such as:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card ownership
- Active Membership
- Estimated Salary

---

## Repository Structure
-├── Bank_Customer_Churn_Prediction_Using_Mac.pdf # Literature review paper<br>
-├── Churn_Modelling.csv # Dataset<br>
-├── DataScience_Project.ipynb # Jupyter Notebook (Model training & evaluation)<br>
-├── README.md # Project Documentation<br>


---

## Features
- Data preprocessing & cleaning
- Exploratory Data Analysis (EDA) with visualizations
- Multiple Machine Learning models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - K-Nearest Neighbors
  - AdaBoost
  - Support Vector Machine 
- Model evaluation with:
  - Accuracy
  - Confusion Matrix
  - ROC Curve & AUC Score
  - Precision, Recall, F1-Score

---

## Results (Example)
| Model                  | Accuracy |
|-------------------------|----------|
| Logistic Regression     | ~77%     |
| Decision Tree           | ~79%     |
| Random Forest           | ~87%     |
| KNN                     | ~83%     |
| AdaBoost                | ~84%     | 
| SVM                     | ~72%     |

Random Forest performed the best in this project.

---

## Installation & Usage 🛠️

1.  **Clone this repository:**
    ```bash
    git clone [https://github.com/EmanayArshad/bank-customer-churn-prediction.git](https://github.com/EmanayArshad/bank-customer-churn-prediction.git)
    cd bank-customer-churn-prediction
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook DataScience_Project.ipynb
    ```
