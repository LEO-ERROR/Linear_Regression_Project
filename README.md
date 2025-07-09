# Linear_Regression_Project
# LR_Delivery_Time_Prediction

## 📌 Objective
This project aims to build a **linear regression model** to predict delivery time for orders placed on Porter's intra-city logistics platform. By leveraging data on orders, stores, and delivery operations, we intend to support better operational planning and customer satisfaction.

---

## 📊 Dataset Overview
The dataset contains details of parcel deliveries and includes:
- **Order features** (e.g., total items, subtotal)
- **Store features** (e.g., category, distance from customer)
- **Operational features** (e.g., number of delivery partners on shift)
- **Target**: Actual delivery time (in timestamp)

---

## 🧪 Project Steps

1. **Data Loading & Preprocessing**
   - Fixing data types
   - Handling missing values
   - Splitting into train and validation sets

2. **Exploratory Data Analysis (EDA)**
   - Distribution of numerical and categorical features
   - Correlation analysis
   - Outlier detection and treatment

3. **Model Building**
   - Feature scaling
   - Simple linear regression
   - Recursive Feature Elimination (RFE)

4. **Evaluation & Inference**
   - Residual analysis
   - Coefficient interpretation
   - Business insights and recommendations

---

## 🧠 Key Insights
- Distance and number of busy dashers are strong predictors of delivery time.
- Outliers and skewness were addressed to improve model reliability.
- RFE helped in selecting the most relevant features for optimal performance.

---

## 📎 File Structure



---

## ⚙️ Requirements
To run the notebook:
```bash
pip install -r requirements.txt
