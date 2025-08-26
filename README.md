# Restaurant Success Analytics: Decoding Yelp Ratings with Machine Learning

**Author:** Francisco Barbosa  
**GitHub:** [@Tuminha](https://github.com/Tuminha)  
**Email:** cisco@periospot.com  
**Twitter:** [@cisco_research](https://twitter.com/cisco_research)

---

## 🍽️ Project Overview

The restaurant industry is more competitive than ever, with online reviews becoming the make-or-break factor for new establishments. As someone passionate about data science and the culinary world, I'm embarking on a mission to decode the secret ingredients of restaurant success on Yelp.

**The Big Question:** *If I were to open my dream restaurant tomorrow, what factors should I prioritize to achieve the highest Yelp rating?*

This project uses supervised machine learning models for regression to predict restaurant ratings. The goal is to build and evaluate various regression models to accurately forecast restaurant ratings based on available features such as location, cuisine type, price range, and other relevant characteristics.

## 🎯 What I'm Building

Using real Yelp data and multiple linear regression, I'll uncover the key drivers behind restaurant ratings. This isn't just an academic exercise—it's a practical guide for anyone looking to understand what makes restaurants thrive in the digital age.

**My Approach:**
- 📊 **Data Exploration**: Deep dive into Yelp's comprehensive dataset
- 🧹 **Data Preparation**: Clean and engineer features for optimal model performance  
- 🤖 **Model Development**: Build and tune a multiple linear regression model
- 💡 **Insight Generation**: Extract actionable recommendations for restaurant success

## 📁 Dataset Overview

I'm working with six rich datasets from Yelp, each offering unique insights into restaurant performance:

* **`yelp_business.json`**: Core establishment data (location, attributes, categories)
* **`yelp_review.json`**: Review metadata and sentiment indicators
* **`yelp_user.json`**: User engagement and profile characteristics
* **`yelp_checkin.json`**: Customer visit patterns and timing data
* **`yelp_tip.json`**: Quick feedback and tip engagement metrics
* **`yelp_photo.json`**: Visual content and photo engagement data

## 🚀 Project Goals

By the end of this analysis, I'll be able to answer:
- Which restaurant attributes have the strongest correlation with high ratings?
- How important are factors like location, cuisine type, and price range?
- What role does customer engagement (photos, tips, check-ins) play in ratings?
- Can I build a reliable model to predict restaurant success?

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

3. **Download the Yelp datasets:**
   - The Yelp datasets are not included in this repository due to file size limits
   - Download the datasets from the [Codecademy project page](https://www.codecademy.com/learn/paths/data-science)
   - Place the following files in your project directory:
     - `yelp_business.json`
     - `yelp_review.json`
     - `yelp_user.json`
     - `yelp_checkin.json`
     - `yelp_tip.json`
     - `yelp_photo.json`

4. **Install additional dependencies (if needed):**
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

## 📊 Project Progress

### ✅ Completed Tasks

1. **Set Up the Project** ✅
   - Downloaded and loaded all 6 Yelp datasets
   - Created comprehensive Jupyter notebook for analysis
   - Set up proper data display options for large datasets

2. **Explore the Datasets** ✅
   - Loaded all datasets: business, review, user, checkin, tip, and photo data
   - Analyzed data structure and dimensions
   - Identified common features across datasets (`business_id`)
   - Explored data types and basic statistics
   - Found 188,593 businesses in the dataset

### 🔄 In Progress Tasks

3. **Merge the Datasets** 🔄
   - Need to combine all datasets using `business_id` as the key
   - Perform left joins to preserve all business data

### 📋 Remaining Tasks

4. **Prepare and Clean the Data**
   - Remove unnecessary features (address, attributes, etc.)
   - Handle missing values (replace NaN with 0)
   - Focus on continuous and binary features for regression

5. **Correlation Analysis and Feature Selection**
   - Analyze correlations between features and Yelp ratings
   - Identify most predictive features
   - Create visualizations of key relationships

6. **Split Data into Training and Testing Sets**
   - Use train_test_split with 80/20 ratio
   - Set random_state for reproducibility

7. **Train the ML Model**
   - Implement multiple linear regression
   - Train on different feature subsets
   - Compare model performance

8. **Evaluate the Model**
   - Calculate R² scores for training and testing data
   - Analyze model coefficients
   - Create prediction vs actual plots

9. **Experiment with Potential Improvements**
   - Test different feature combinations
   - Optimize model parameters
   - Compare multiple regression approaches

10. **Share Your Model**
    - Document findings and insights
    - Create final predictions for sample restaurant
    - Prepare project for portfolio submission

## 🎯 Current Status

**Progress: 2/10 tasks completed (20%)**

The project is off to a strong start with comprehensive data exploration completed. The next major milestone is merging all datasets and beginning the data preparation phase.

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

Let's dive into the data and start uncovering the patterns that separate 5-star establishments from the rest!
