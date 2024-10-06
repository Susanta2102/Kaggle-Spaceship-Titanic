
# 🚀 **Kaggle Spaceship Titanic - Machine Learning Project** 🌌



## 📝 **Project Overview**

Welcome to my **Kaggle Spaceship Titanic** competition project! 🎯 The challenge is to predict whether a passenger was transported to another dimension during the **Spaceship Titanic** disaster.

Explore the full project notebook with code, explanations, and visualizations here:  
👉 [**Kaggle Notebook**](https://www.kaggle.com/code/susanta21/kaggle-spaceship-titanic)

## 🚢 **Problem Statement**

The goal is to build a machine learning model to predict the `Transported` status of passengers based on the following features:

- **PassengerId** 🆔: Unique identifier for each passenger.
- **HomePlanet** 🪐: The planet the passenger originated from.
- **CryoSleep** 💤: Whether the passenger was in suspended animation.
- **Cabin** 🛏️: Cabin details of the passenger.
- **Destination** 🌠: Destination planet for the passenger.
- **Age** 🎂: Age of the passenger.
- **VIP** 💎: VIP service status.
- **RoomService, FoodCourt, ShoppingMall, Spa, VRDeck** 🛍️: Expenditure in these facilities.
- **Name** 👤: Passenger's name.
- **Transported** ✅/❌: The target variable indicating if the passenger was transported.

## 🔍 **Approach**

### 1. **Data Exploration and Preprocessing** 🧹
   - **Handling Missing Values**: Cleaned up missing data to ensure consistent model input.
   - **Feature Engineering** 🛠️: Extracted new features from existing ones (like deck and cabin number from `Cabin`).
   - **Normalization** 📊: Scaled numerical features for better performance.

### 2. **Model Selection** 🤖
   Experimented with several machine learning models to find the best one:
   - **Logistic Regression**
   - **Decision Trees**
   - **Random Forest**
   - **Gradient Boosting**
   - **XGBoost**

### 3. **Model Tuning & Evaluation** 🔧
   - **Hyperparameter Tuning**: Fine-tuned models for optimal accuracy.
   - **Evaluation Metrics**: Used accuracy, F1 score, and ROC-AUC to assess model performance.

### 4. **Final Model & Prediction** 🎉
   The best-performing model was selected for generating final predictions, achieving significant accuracy on the test data.

## 💻 **Technologies Used**

- **Python** 🐍: The core programming language.
- **Pandas** 📑: For data manipulation and preprocessing.
- **Matplotlib & Seaborn** 📊: For data visualization.
- **Scikit-learn** 🧠: For building and evaluating machine learning models.
- **Kaggle Notebooks** 📒: Used to develop and run the entire project.

## 🎯 **Results**

The final model achieved an impressive accuracy score of `81` (replace with your actual score) on the test data. 🚀



## 🛠️ **How to Use**

To reproduce the results from this project, follow these steps:

1. **Clone this repository**:  
   ```bash
   git clone https://github.com/your-repo/spaceship-titanic.git
   ```

2. **Install dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook**:  
   ```bash
   jupyter notebook kaggle-spaceship-titanic.ipynb
   ```

## 📌 **Kaggle Notebook**

For the full walkthrough of the solution, including code, insights, and visualizations, visit the Kaggle notebook here:  
👉 [**View Kaggle Notebook**](https://www.kaggle.com/code/susanta21/kaggle-spaceship-titanic)

## 🏆 **Conclusion**

The **Spaceship Titanic** competition provided an exciting opportunity to experiment with machine learning models for binary classification. The notebook demonstrates feature engineering, model selection, and performance tuning to achieve optimal results.

Thank you for checking out the project! 🌟 Feel free to reach out if you have any questions or suggestions.
