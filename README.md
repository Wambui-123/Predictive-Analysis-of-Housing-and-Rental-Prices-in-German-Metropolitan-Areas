# Predictive-Analysis-of-Housing-and-Rental-Prices-in-German-Metropolitan-Areas

# Predictive Analysis of Apartment Rental Prices in Germany

## 📌 Project Overview

This project applies **machine learning techniques** to predict apartment rental prices in Germany based on property characteristics and regional information. The goal is to understand which factors most influence rental prices and to build a regression model capable of estimating rent for new listings.

The project is implemented in **Python** using common data science and machine learning libraries and is presented as a Jupyter Notebook.

---

## 🧠 Problem Statement

Rental prices in Germany vary significantly depending on:

* Apartment size
* Number of rooms
* Year of construction
* Geographic location (region / city)

This project aims to:

* Analyze these factors
* Train a regression model
* Predict apartment rental prices using historical data

---

## 🗂 Dataset

* **Source**: `immo_data.csv`
* **Content**: Real estate listing data including apartment features and regional indicators
* **Target Variable**: Rental price

### Example Features Used

* `livingSpace`
* `noRooms`
* `yearConstructed`
* Regional dummy variables (e.g. `regio1_Berlin`, `regio2_Berlin`)

---

## 🛠 Technologies & Libraries

* **Python**
* **Pandas** – data manipulation
* **NumPy** – numerical operations
* **Matplotlib / Seaborn** – data visualization
* **Scikit-learn** – machine learning models & evaluation

---

## ⚙️ Methodology

1. **Data Loading & Cleaning**

   * Load dataset using Pandas
   * Handle missing values
   * Select relevant features

2. **Exploratory Data Analysis (EDA)**

   * Inspect data distribution
   * Identify correlations between variables

3. **Model Building**

   * Split data into training and testing sets
   * Train a **Linear Regression** model

4. **Model Evaluation**

   * Mean Absolute Error (MAE)
   * Mean Squared Error (MSE)
   * R² Score

5. **Prediction**

   * Predict rental prices for example apartments

---

## 📊 Model Evaluation Metrics

The model is evaluated using:

* **MAE** – average prediction error
* **MSE** – penalizes large errors
* **R² Score** – explains variance in rental prices

---

## 🧪 Example Prediction

The notebook includes example apartment configurations (e.g. size, rooms, location) and predicts their rental prices using the trained model.

---

## ▶️ How to Run the Project

1. Clone the repository
2. Install required dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Place `immo_data.csv` in the project directory
4. Open and run the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

---

## 🚀 Future Improvements

* Try advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Feature scaling and engineering
* Include additional regional or economic data

---

## 👤 Author

Created as a machine learning project for predictive analysis of real estate rental prices in Germany.

---

## 📄 License

This project is for educational and research purposes.
