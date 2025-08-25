# Restaurant Rating Prediction - Regression Cumulative Project

## Project Overview

This project uses supervised machine learning models for regression to predict restaurant ratings. The goal is to build and evaluate various regression models to accurately forecast restaurant ratings based on available features such as location, cuisine type, price range, and other relevant characteristics.

## Project Description

As part of the Codecademy Data Science curriculum, this cumulative project demonstrates the application of regression techniques to solve a real-world prediction problem. The project involves data preprocessing, feature engineering, model selection, training, and evaluation to create an effective restaurant rating prediction system.

## Features

- **Data Exploration**: Comprehensive analysis of restaurant data and rating patterns
- **Data Preprocessing**: Cleaning, handling missing values, and feature engineering
- **Model Implementation**: Multiple regression algorithms including:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Random Forest Regression
  - Gradient Boosting Regression
- **Model Evaluation**: Performance comparison using metrics like RMSE, MAE, and R²
- **Visualization**: Data insights and model performance visualizations

## Technologies Used

- **Python 3.11**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **scikit-learn** - Machine learning algorithms and tools
- **matplotlib** - Data visualization
- **scipy** - Scientific computing

## Project Structure

```
restaurant_rating/
├── README.md                 # Project documentation
├── data/                     # Dataset files
├── notebooks/                # Jupyter notebooks for analysis
├── src/                      # Source code modules
├── models/                   # Trained model files
├── results/                  # Output files and visualizations
├── requirements.txt          # Python dependencies
└── codeacademy/             # Virtual environment
```

## Getting Started

### Prerequisites

- Python 3.11 or higher
- Virtual environment (already set up in `codeacademy/`)

### Installation

1. **Clone or navigate to the project directory:**
   ```bash
   cd /Users/franciscoteixeirabarbosa/Dropbox/CodeAcademy/restaurant_rating
   ```

2. **Activate the virtual environment:**
   ```bash
   source codeacademy/bin/activate
   ```

3. **Install additional dependencies (if needed):**
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. **Data Preparation:**
   - Load and explore the restaurant dataset
   - Perform data cleaning and preprocessing
   - Handle missing values and outliers

2. **Model Training:**
   - Split data into training and testing sets
   - Train multiple regression models
   - Perform hyperparameter tuning

3. **Model Evaluation:**
   - Evaluate models using cross-validation
   - Compare performance metrics
   - Select the best performing model

4. **Prediction:**
   - Make predictions on new restaurant data
   - Generate insights and recommendations

## Key Learning Objectives

- Apply regression techniques to real-world data
- Understand the importance of feature engineering
- Compare different regression algorithms
- Evaluate model performance using appropriate metrics
- Interpret model results and make data-driven decisions

## Model Performance Metrics

The project evaluates models using:
- **Root Mean Square Error (RMSE)**: Measures prediction accuracy
- **Mean Absolute Error (MAE)**: Average absolute difference between predicted and actual ratings
- **R-squared (R²)**: Proportion of variance explained by the model
- **Cross-validation scores**: Assess model generalization

## Expected Outcomes

- A trained regression model capable of predicting restaurant ratings
- Insights into factors that most influence restaurant ratings
- Comparison of different regression techniques
- Recommendations for restaurant rating prediction

## Future Enhancements

- Feature selection optimization
- Advanced ensemble methods
- Deep learning approaches
- Real-time prediction system
- Web application interface

## Contributing

This is a Codecademy cumulative project. Contributions and suggestions for improvement are welcome.

## License

This project is created for educational purposes as part of the Codecademy Data Science curriculum.

---

**Note**: This project demonstrates practical application of supervised machine learning regression techniques for predicting restaurant ratings, combining data science fundamentals with real-world problem-solving.
