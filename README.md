# Student Performance Prediction

This project predicts students' **math, reading, and writing scores** based on various features such as **gender**, **lunch type**, **test preparation course**, and **parental education level** using **linear regression** and other machine learning models.

## Dataset

The dataset contains information on student performance across three subjects:
- **Math score**
- **Reading score**
- **Writing score**

Other features include:
- **Gender**: Male or Female
- **Race/Ethnicity**
- **Parental level of education**
- **Lunch type**: Standard or Free/Reduced
- **Test preparation course**: Completed or Not

The dataset is used to explore how these features influence students' performance and to predict individual scores based on these attributes.

## Project Overview

1. **Data Exploration**:  
   Initial analysis was done to explore the distribution of the scores and understand the relationship between features.

2. **Feature Engineering**:  
   Categorical variables such as gender, lunch type, and test preparation course were processed using **One-Hot Encoding** to convert them into numerical values.

3. **Modeling**:  
   A **Linear Regression model** was implemented to predict the students' math scores. Other models like **Decision Trees** and **Random Forests** were also tested, but **Linear Regression** produced the best results.

4. **Evaluation**:  
   The performance of the model was evaluated using **Mean Squared Error (MSE)** and **R-squared (R²)** metrics.

## Project Results

The final model achieved:
- **MSE**: 168.754
- **R² Score**: 0.255

These metrics indicate how well the model was able to predict the math scores. Further improvements could be made by **feature engineering**, **scaling** features, or testing other advanced models.

## Requirements

To run this project locally, make sure you have the following libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install them using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

```

## How to Run the Project

1. Clone this repository to your local machine

```bash
git clone https://github.com/oluwaseyiae/student-performance-prediction.git

```
2. Navigate to the project folder

```bash
cd student-performance-prediction
```
3. Run the Python script

```bash
jupyter notebook student-performance_v1.ipynb
```
## Future Improvements

- Explore **non-linear models** (e.g., **Random Forest, Gradient Boosting**).
- Investigate further **feature engineering** (e.g., interaction terms, polynomial features).
- Apply **cross-validation** for more robust model evaluation.
- Experiment with **hyperparameter tuning** to improve model performance.


