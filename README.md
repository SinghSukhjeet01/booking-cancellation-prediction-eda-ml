# Hotel Booking Cancellation Prediction

Last-minute hotel reservation cancellations can cause significant inefficiencies and revenue losses for the hospitality industry. This project explores the use of machine learning to predict hotel booking cancellations, helping hotels proactively manage operations and improve customer satisfaction.

By analyzing booking records and applying classification models, this project aims to determine whether a reservation is likely to be cancelled based on historical data.

---

## 🔍 Dataset Identification

I explored different types of datasets and platforms with the aim of obtaining recent, accurate, and business-relevant data. After evaluating several options, I selected the "Hotel Reservations Dataset" from Kaggle, a widely used platform for high-quality datasets.
### 📌 Dataset Summary:
- **Source**: https://www.kaggle.com
- **Size**: 36,275 entries and 19 attributes
- **Target Variable**: `booking_status` (Cancelled / Not_Cancelled)
- **Attributes Include**:
  - Number of adults
  - Number of weeknights and weekend nights
  - Type of room reserved
  - Meal plan selected
  - Booking channel
  - Special requests
  - Reservation status

The dataset contains comprehensive and structured information related to guest bookings, allowing for insightful feature analysis and prediction modelling.

---

## 📊 Project Workflow

1. **Dataset Acquisition**  
2. **Exploratory Data Analysis (EDA)**  
3. **Data Cleaning & Preprocessing**  
4. **Feature Selection**  
5. **Model Training & Evaluation**  
6. **Interpretation of Results**

All tasks were performed in a **Google Colab Notebook** using the following tools:

- `Python`
- `Pandas`, `NumPy` – Data manipulation
- `Matplotlib`, `Seaborn` – Visualization
- `Scikit-learn` – Machine learning

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)

### 📈 Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

✅ Conclusion

This study demonstrates how predictive modelling can be effectively used to forecast hotel booking cancellations. By using business-oriented, real-world data, we show the potential of machine learning in supporting decision-making and resource optimization in the hospitality industry.

