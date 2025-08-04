# 💳 Credit Card Customer Churn Prediction (TensorFlow + Keras)

Predicting whether a customer is likely to **churn** (leave the credit card service) using **deep learning**. This project leverages TensorFlow and Keras to build an accurate neural network that understands customer behavior and helps banks improve retention strategies.

---

## 📌 Project Overview

Customer churn is a huge challenge in the financial industry. This project uses a **neural network model** to classify whether a customer will churn based on their behavior and transaction patterns.

The goal: Help credit card companies **retain valuable customers**.

---

## 🧠 Features

- TensorFlow/Keras-based Neural Network Model 🧠
- Full Data Preprocessing & Normalization
- Exploratory Data Analysis (EDA)
- Model Evaluation using Accuracy, Loss, Confusion Matrix
- Business Recommendations based on churn insights

---

## 🗂️ Dataset

Used from Kaggle:  
[📥 Credit Card Churn Dataset](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)

Key columns include:
- `Customer_Age`, `Gender`, `Credit_Limit`, `Total_Trans_Ct`
- `Attrition_Flag` (target column)

---

## ⚙️ Tech Stack

- Python 🐍  
- TensorFlow + Keras 🔥  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Jupyter Notebook  

---

## 🏗️ Neural Network Architecture

```python
model = Sequential()
model.add(Dense(128, activation='relu', input_shape=(X_train.shape[1],)))
model.add(Dense(64, activation='relu'))
model.add(Dense(1, activation='sigmoid'))
```

## Compiled with:

```python

model.compile(optimizer='adam', loss='binary_crossentropy', metrics=['accuracy'])
```

✅ The deep learning model performed well in identifying churned customers!

## 📌 Key Insights
Customers with low transaction count and credit limit were more likely to churn.

Tenure and inactivity months were strong churn indicators.

Banks can use this model to proactively reach out to at-risk customers.

## 💡 Future Upgrades
Add dropout layers to reduce overfitting

Use callbacks like EarlyStopping and ModelCheckpoint

Try hyperparameter tuning

Deploy model via Streamlit or Flask

Add SHAP for interpretability

## 👩‍💻 Author
Hi! I'm Muskan Tariq, an AI student exploring the world of deep learning and solving real-world problems with data.
Check out my journey on:
🔗 [LinkedIn](https://www.linkedin.com/in/muskan-tariq-095a50282)  
📸 [Instagram](https://www.instagram.com/ai_enthusiast86?igsh=dnRyenAwdTBxdTZ6)  
🎥 [YouTube](https://youtube.com/@ai_enthusiast86?si=bYV1AgkBoCMVUBiK) 

🌟 Support
If this project helped you, drop a ⭐ on GitHub, share it with friends, or tag me online — let’s grow together! 💖

Let me know if you want a `requirements.txt` too or a Streamlit UI for it — I’ll serve it hot and fast ☕😎
