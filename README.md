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

3. **Merge the Datasets** ✅
   - Successfully combined all 6 datasets using `business_id` as the key
   - Performed left joins to preserve all business data
   - Created comprehensive merged dataset with all features

4. **Prepare and Clean the Data** ✅
   - Removed irrelevant features (address, attributes, business_id, etc.)
   - Identified and handled missing values
   - Focused on continuous and binary features suitable for regression
   - Prepared clean dataset for machine learning analysis

5. **Correlation Analysis and Feature Selection** ✅
   - Analyzed correlations between all features and Yelp ratings
   - Identified `average_review_sentiment` as strongest predictor (0.78 correlation)
   - Created feature importance ranking for model development
   - Generated correlation heatmap visualizations

6. **Split Data into Training and Testing Sets** ✅
   - Used train_test_split with 80/20 ratio
   - Set random_state for reproducibility
   - Prepared data for multiple model iterations

7. **Train the ML Model** ✅
   - Implemented multiple linear regression models
   - Trained on different feature subsets (simple, engagement, comprehensive)
   - Created "Danielle's Delicious Delicacies" prediction model
   - Achieved realistic prediction of 3.89 stars

8. **Evaluate the Model** ✅
   - Calculated R² scores for training and testing data
   - Analyzed model coefficients and feature importance
   - Created prediction vs actual plots
   - Evaluated model performance across different feature combinations

9. **Experiment with Potential Improvements** ✅
   - Tested different feature combinations and model parameters
   - Implemented advanced analyses beyond the core requirements
   - Created comprehensive restaurant insights and predictions

10. **Share Your Model** ✅
    - Documented findings and insights in comprehensive README
    - Created final predictions for sample restaurant
    - Prepared project for portfolio submission with professional documentation

## 🎯 Current Status

**Progress: 10/10 tasks completed (100%)**

🎉 **PROJECT COMPLETE!** All Codecademy requirements have been successfully completed, along with additional advanced analyses including cuisine prediction, restaurant clustering, vibe analysis, and social media impact assessment.

## 🎯 Key Findings & Insights

### **🏆 Most Predictive Features:**
- **`average_review_sentiment`** (0.78 correlation) - Customer satisfaction is the primary driver
- **`average_review_length`** (-0.28 correlation) - Longer reviews may indicate more detailed feedback
- **`has_bike_parking`** (0.068 correlation) - Infrastructure amenities matter
- **`takes_credit_cards`** (0.038 correlation) - Payment convenience influences ratings

### **🍽️ Restaurant Success Factors:**
- **Customer sentiment** in reviews is the strongest predictor of ratings
- **Infrastructure amenities** (bike parking, credit cards) positively impact ratings
- **Customer engagement** (tips, check-ins) shows correlation with success
- **Price range** has minimal direct impact on ratings

### **📊 Model Performance:**
- **Realistic predictions** for new restaurants (3.89 stars for Danielle's Delicious Delicacies)
- **Conservative model** that doesn't overfit to training data
- **Feature importance** ranking provides actionable insights for restaurant owners

## 🚀 Advanced Analyses Completed

### **🍕 Cuisine Prediction:**
- Built model to predict restaurant cuisine based on reviewer characteristics
- Analyzed how different user demographics prefer different cuisines
- Identified user behavior patterns by restaurant type

### **🏪 Restaurant Clustering:**
- Created similarity clusters based on features beyond cuisine
- Identified 5 distinct restaurant types with unique characteristics
- Analyzed cluster performance and customer engagement patterns

### **🎭 Restaurant Vibes Analysis:**
- Categorized restaurants into vibes: Upscale, Family-Friendly, Trendy/Casual, Weekend Destination, Standard
- Analyzed rating patterns and customer behavior by vibe
- Identified which vibes attract the most engaged customers

### **📱 Social Media Impact:**
- Analyzed correlation between social engagement and ratings
- Measured impact of cool votes, funny votes, tips, and photos
- Identified social media strategies that correlate with higher ratings

## Expected Outcomes

✅ **A trained regression model capable of predicting restaurant ratings**
✅ **Insights into factors that most influence restaurant ratings**
✅ **Comparison of different regression techniques**
✅ **Recommendations for restaurant rating prediction**
✅ **Advanced analyses beyond core requirements**

## Future Enhancements

- **Deep learning approaches** for more complex pattern recognition
- **Real-time prediction system** for live restaurant data
- **Web application interface** for easy model access
- **Geographic analysis** to understand location-based patterns
- **Temporal analysis** to track rating changes over time

## Contributing

This is a Codecademy cumulative project. Contributions and suggestions for improvement are welcome.

## License

This project is created for educational purposes as part of the Codecademy Data Science curriculum.

---

**Note**: This project demonstrates practical application of supervised machine learning regression techniques for predicting restaurant ratings, combining data science fundamentals with real-world problem-solving.

Let's dive into the data and start uncovering the patterns that separate 5-star establishments from the rest!
