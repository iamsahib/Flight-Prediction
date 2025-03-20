# Flight Price Prediction

## Project Overview
This project aims to predict flight ticket prices using machine learning techniques. The dataset includes various flight details such as airline, departure time, arrival time, duration, number of stops, and ticket price. The workflow involves data cleaning, feature engineering, exploratory data analysis (EDA), and model training.

## Libraries Used
The following Python libraries are used in this project:
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computations
- **matplotlib & seaborn** - Data visualization
- **scikit-learn (sklearn)** - Machine learning models and preprocessing
- **warnings** - Suppressing unnecessary warnings

## Features Added
### Data Preprocessing & Feature Engineering
- **Date-Time Features:**
  - Converted `Date_of_Journey`, `Dep_Time`, and `Arrival_Time` into datetime format
  - Extracted day, month, and hour information
- **Handling Missing Values:**
  - Identified and removed missing values
- **Encoding Categorical Variables:**
  - Applied one-hot encoding and label encoding for categorical features
- **Feature Engineering:**
  - Extracted `Total_Stops` as an important predictor
  - Split `Duration` into `Duration_hours` and `Duration_minutes`

## Model Training
Various machine learning algorithms were implemented for price prediction:
- **Linear Regression**
- **Decision Trees**
- **Random Forest**

## Recommendations
- Perform hyperparameter tuning to improve model accuracy
- Try ensemble methods like XGBoost for better performance
- Check feature importance to eliminate unnecessary predictors
- Apply cross-validation for robust model evaluation

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/iamsahib/flight-price-prediction.git
   ```
2. Navigate to the project folder:
   ```bash
   cd flight-price-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook to explore the dataset and train the model.

## Conclusion
This project successfully demonstrates flight price prediction using machine learning. Future improvements include feature selection, hyperparameter tuning, and testing advanced models for better accuracy.

---

Feel free to contribute to this project or suggest improvements!

