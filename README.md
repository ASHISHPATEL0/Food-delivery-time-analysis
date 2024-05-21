# Food Delivery Time Analysis

This project focuses on analyzing a food delivery dataset to predict delivery times using regression techniques. The analysis is performed in a Jupyter Notebook, and the key objectives are:

- **Data Preprocessing**: Handling missing values, encoding categorical variables, and creating new features from the given data.
- **Feature Engineering**: Deriving relevant features from the dataset, such as distance between restaurant and delivery location, order preparation time, and time-based features.
- **Feature Selection**: Applying Chi-squared test to identify the most significant features influencing delivery time.
- **Model Selection and Evaluation**: Evaluating multiple regression models, including Random Forest, Gradient Boosting, and Extra Trees, using metrics like RMSE, MSE, MAE, and R-squared score.
- **Hyperparameter Tuning**: Optimizing the hyperparameters of the best-performing model (Random Forest Regressor) using RandomizedSearchCV for improved prediction accuracy.

## Prerequisites

The following libraries are required to run this project:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- geopy (for calculating distance between coordinates)

## Usage

1. Clone the repository or download the Jupyter Notebook file.
2. Make sure you have the required libraries installed.
3. Open the Jupyter Notebook file in your preferred environment.
4. Run the cells sequentially to follow the analysis process.

## Results

The analysis identifies the critical factors influencing food delivery time, such as order preparation time, distance between restaurant and delivery location, and weather conditions. The Random Forest Regressor model, with optimized hyperparameters, achieved the highest accuracy in predicting delivery times, enabling data-driven decision-making for efficient food delivery operations.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.
