# Laptop Price Prediction

This project uses machine learning to predict laptop prices based on specifications like CPU, RAM, storage, etc. It leverages a dataset of laptop specifications and corresponding prices to train a model capable of estimating prices for new laptops.

## Project Steps

1. **Data Cleaning:** Handling missing values, removing duplicates, and cleaning inconsistent data.
2. **Exploratory Data Analysis (EDA):** Visualizing data patterns and relationships between features and price.
3. **Feature Engineering:** Transforming and creating new features to improve model accuracy (e.g., extracting CPU brand, calculating pixels per inch).
4. **Model Selection:** Evaluating various machine learning models to find the best fit.
5. **Model Training:** Training the selected model on a portion of the dataset.
6. **Model Evaluation:** Assessing the model's performance on a separate test dataset using metrics like R2 score and Mean Absolute Error (MAE).

## Model

The final model is a stacking regressor that combines:

* Random Forest
* Gradient Boosting
* XGBoost

This ensemble approach enhances prediction accuracy.

## Results

The model achieves:

* R2 score: 0.89
* Mean Absolute Error (MAE): 0.16


## Files

* `laptop_data.csv`: Dataset used for the project
* `df.pkl`:  Cleaned and processed DataFrame
* `pipe.pkl`: Trained machine learning model

## Libraries Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn

  The final application will look like:
  ![Screenshot 2024-10-06 233048](https://github.com/user-attachments/assets/a774da64-0bb9-49bc-a179-ea7d8f73936f)
