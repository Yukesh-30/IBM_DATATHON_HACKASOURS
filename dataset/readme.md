# 🍽️ Restaurant Food Demand Forecasting

## 📘 Overview

This project focuses on **demand forecasting for restaurant dishes** using advanced time series models.  
By predicting the number of food units sold daily across multiple restaurant localities, this project aims to **reduce food wastage**, improve **inventory planning**, and **optimize kitchen operations**.

---

## 📊 About the Dataset

This dataset contains **daily sales records of food dishes** across various restaurant localities.  
Each row represents the **number of units sold (`units_sold`)** for a specific dish on a particular date, along with rich contextual and descriptive features.

### 🧩 Dataset Features

#### 🕒 Time-Based Features:
- **date** – Date of the record.  
- **weekday** – Day of the week (e.g., Monday, Tuesday).  
- **month** – Month of the year.  
- **season** – Season indicator (e.g., summer, winter).  
- **is_weekend** – Whether the day is a weekend.  
- **working_day** – Indicates if the day is a working day.  

These attributes help capture **weekly and seasonal sales trends**.

#### 🍛 Dish-Related Features:
- **category** – Type of cuisine or menu category (e.g., appetizer, main course, dessert).  
- **veg_nonveg** – Indicates if the dish is vegetarian or non-vegetarian.  
- **ingredient** – Key ingredient or base of the dish.  
- **foodtype** – Describes cuisine type (e.g., Indian, Chinese, Italian).  
- **meal_type** – Breakfast, lunch, dinner, or snack.  
- **spice_level** – Level of spiciness.  
- **size** – Portion size (e.g., small, medium, large).  

These features represent **culinary characteristics** influencing customer preferences.

#### 🏙️ Restaurant-Level Features:
- **restaurant_locality** – Location of the restaurant.  

This captures **geographical variability in demand**.

#### 💰 Economic & Quality Features:
- **price_per_unit** – Selling price of a dish.  
- **price_mean** – Average price of similar dishes.  
- **rating** – Customer rating of the dish.  
- **dish_popularity** – Popularity score based on historical demand.  

These features contribute to understanding **pricing and quality-driven demand changes**.

#### 🎉 External & Event-Based Features:
- **is_holiday** – Whether the date is a holiday.  
- **holiday_religion** – Type of holiday (e.g., Hindu, Muslim, Christian).  
- **is_festival** – Indicates if it’s a festival period.  

These help model **demand spikes during cultural or religious events**.

---

## 🎯 Objective

The primary goal of this project is to **forecast daily food demand** at different restaurants to:
- Minimize **food wastage** caused by overproduction.  
- Ensure **sufficient stock** to meet customer demand.  
- Optimize **supply chain and kitchen management**.  
- Enable **data-driven menu planning** and **dynamic pricing**.

---

## 🧠 Methodology

We use **machine learning** and **deep learning models** such as:
- **LSTM (Long Short-Term Memory Networks)** for capturing temporal dependencies.
- **Gradient Boosting / Random Forests** for feature-driven prediction.
- **Data preprocessing & feature engineering** to handle categorical, temporal, and event-based features.

---

## ⚙️ Project Workflow

1. **Data Collection & Cleaning**  
   - Handling missing values, encoding categorical variables, and normalizing data.

2. **Feature Engineering**  
   - Extracting temporal features, aggregating demand patterns, and identifying trends.

3. **Model Training**  
   - Training and tuning models such as LSTM for time series forecasting.

4. **Evaluation**  
   - Using metrics like **MAE (Mean Absolute Error)** and **RMSE (Root Mean Squared Error)**.

5. **Deployment**  
   - Serving demand forecasts through an API or dashboard for real-time decision-making.

---

## 🧾 Example Use Cases

- Predict next-day demand for each restaurant-dish pair.  
- Identify dishes likely to be under or overproduced.  
- Adjust ingredient procurement schedules.  
- Optimize cooking quantities to **minimize waste** while **maximizing sales**.

---

## 🧰 Tech Stack

- **Python**, **Pandas**, **NumPy**, **Scikit-learn**  
- **TensorFlow / PyTorch** (for LSTM)  
- **Matplotlib / Seaborn** (for visualization)  
- **Jupyter Notebook** for experimentation

---

## 📈 Expected Outcome

- Accurate demand forecasting for each dish across localities.  
- Reduction in food wastage and improved resource efficiency.  
- Enhanced profitability and sustainability in restaurant operations.

---


