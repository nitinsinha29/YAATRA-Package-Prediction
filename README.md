 ✈️ YAATRA: Travel Package Purchase Prediction

 *A Machine Learning solution to predict customer travel interests and optimize marketing strategies.*


📖 Project Overview
This project focuses on developing a predictive model to identify individuals likely to purchase **Yaatra travel packages**.
By leveraging **Machine Learning**, we can help the marketing team target the right customers, reducing costs and increasing conversation rates.

🎯 Project Goals
* **Predict User Interest:** Classify users as "Potential Buyers" or "Non-Buyers" with high accuracy.
* **Customer Profiling:** Identify key demographics (age, income, city) that drive sales.
* **Targeted Marketing:** Provide data-driven recommendations to the sales team.

---

 📊 Demo & Screenshots
### 1. The Prediction Interface
![image alt](https://github.com/nitinsinha29/YAATRA-Package-Prediction/blob/ebdd8099e3827705b3a31e5ae4241e6014e7c086/yatra%20pic.jpg)

### 2. The Prediction Result
![image alt](https://github.com/nitinsinha29/YAATRA-Package-Prediction/blob/5f5b9b7e6e22380240fcc2b759f65b00b2ce0bf6/164744.jpg)


## 🛠 Tech Stack
* **Language:** 🐍 Python
* **Machine Learning:** Scikit-Learn (Logistic Regression, Random Forest)
* **Data Processing:** Pandas, NumPy
* **Web Framework:** Flask (for the web interface)
* **Frontend:** HTML/CSS

---

## ⚙️ Data Analysis Workflow
1.  **Data Collection:** Dataset retrieved from Kaggle containing customer demographics and past purchase history.
2.  **Data Cleaning:** Handled missing values, treated outliers, and fixed inconsistencies.
3.  **Exploratory Data Analysis (EDA):**
    * Visualized relationships between *Income* and *Travel Frequency*.
    * Segmented customers based on spending habits.
4.  **Model Building:**
    * Selected features using correlation matrices.
    * Trained a **Logistic Regression** model.
    * Evaluated performance using **Accuracy, Confusion Matrix, and ROC Curve**.

---

## 🚀 How to Run This Project
If you want to run the web application on your local machine:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/nitinsinha29/YAATRA-Package-Prediction.git](https://github.com/nitinsinha29/YAATRA-Package-Prediction.git)
    cd YAATRA-Package-Prediction
    ```

2.  **Install Dependencies:**
    ```bash
    pip install numpy pandas flask scikit-learn
    ```

3.  **Run the Application:**
    ```bash
    python app.py
    ```

4.  **Open in Browser:**
    * Go to: `http://127.0.0.1:5000/`
    * Enter customer details to get a prediction.

---

## 🔮 Future Scope
* **Feature Engineering:** Creating new indices from "Income" and "Age" for better precision.
* **Model Comparison:** Testing Gradient Boosting (XGBoost) to improve accuracy.
* **Cloud Deployment:** Deploying the Flask app to AWS or Render for public access.

---

## 👤 Author
**Nitin Sinha**
[LinkedIn Profile](https://www.linkedin.com/in/nitinsinha29)








