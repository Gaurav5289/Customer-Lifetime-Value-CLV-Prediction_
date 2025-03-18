# 📈 Customer Lifetime Value Prediction Project  

## 📝 Overview  
This project aims to predict **Customer Lifetime Value (CLV)** for a business using Python. CLV is a critical metric that helps businesses understand the long-term value of their customers, enabling better decision-making in **marketing, sales, and customer retention strategies**.  

## 📂 Project Contents  

### 🔹 Data Preparation  
- Load historical customer transaction data.  
- Perform **data preprocessing** to calculate **Recency, Frequency, and Monetary Value (RFM)**.  

### 📊 Visualization  
- Use **`matplotlib`** to explore the relationships between **Recency, Frequency, and Log(Monetary Value)**.  
- Plot a **histogram of Log(Monetary Value)** to understand its distribution.  

### 🤖 CLV Prediction Model  
- Implement a **Linear Regression** model using **`scikit-learn`** to predict CLV based on **RFM metrics**.  

### 📏 Model Evaluation  
- Evaluate the model's performance using:  
  - **Mean Squared Error (MSE)**  
  - **R-squared (R²)**  
- Compare **actual vs. predicted CLV values** with a scatter plot.  

### 🛠️ Usage  
- Follow the provided instructions to **predict CLV** for specific customers.  

## 📌 Dependencies  
Ensure you have the following Python libraries installed:  

```bash
pip install pandas numpy matplotlib scikit-learn
