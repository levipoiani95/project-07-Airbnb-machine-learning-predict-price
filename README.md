# 📊 Airbnb Housing Prediction for the city of Rio de Janeiro. 
A complete Python Data Science project focused on statistical modeling, machine learning, and data visualization.
## 💭 Context  
On Airbnb, anyone who owns a room or property of any type (apartment, house, chalet, guesthouse, etc.) can offer their property for daily rental.You create your host profile (the person who makes a property available for daily rental) and create your property listing.
In this listing, the host should describe the property's characteristics as completely as possible, in order to help renters/travelers choose the best property for them (and to make their listing more attractive). 
There are dozens of possible customizations to your listing, from minimum stay, price, number of bedrooms, to cancellation policies, extra fees for additional guests, requirement for identity verification of the renter, etc.
## 🎯 Objective
To build a price prediction model that allows an average person who owns a property to know how much they should charge per day for their property.
Or, for the average landlord, given the property they are looking for, to help them know if that property is attractively priced (below average for properties with the same characteristics) or not.

The goal of this project is to analyze a dataset and build predictive models using classical and ensemble machine learning algorithms. The project compares different regression approaches and evaluates their performance using standard metrics.
## 📝 Abstract
The data was retrieved from the Kaggle website: https://www.kaggle.com/allanbruno/airbnb-rio-de-janeiro.  
The data contains the prices of properties and their respective characteristics for each month.
Prices are given in Brazilian Reais (R$) and the data covers the period from April 2018 to May 2020, with the exception of June 2018, which does not have data available.
The application consumes financial market data through the yfinance library, performs processing and manipulation with Pandas and NumPy, and uses native modules such as datetime and math for calculations, temporal organization, and financial metrics. The data is presented in a clear, interactive, and analysis-oriented way.
## ✏️ Initial Expectations  
- Seasonality can be an important factor, as months like December tend to be quite expensive in Rio de Janeiro.
- The location of the property should make a big difference in the price, since in Rio de Janeiro the location can completely change the characteristics of the place (security, natural beauty, tourist attractions).
- Extras and amenities can be factors that contribute to a significant impact on the price, since we have many old buildings and houses in Rio de Janeiro.

## 🛠️ Development Stacks
- Visual Studio Code (code editor and versioning)
- Python (3.13.5)
- Pandas (data manipulation and preprocessing)
- NumPy (numerical computing)
- PathLib (file and directory manipulation)
- Seaborn (exploratory data analysis and statistical visualization)
- Pyplot/Matplotlib (data visualization support)
- PlotlyExpress (high-level API for creating data maps)
- Scikit-Learn (machine Learning Models, evaluation metrics)

## 📅 Development Steps  
1. Understanding the Challenge
2. Understanding the Company
3. Data Extraction
4. Data Adjustments (Cleaning)
5. Exploratory Analysis
6. Algorithm Modeling
7. Interpretation of Results
8. Deployment/Production

## 🔍 Exploratory Data Analysis (EDA)  
Seaborn was used extensively to:  
- Explore feature distributions
- Analyze correlations between variables
- Detect outliers and patterns
- Visualize relationships between features and the target variable
- Help guide feature selection and model choice

## 🤖 Machine Learning Models  
The following supervised regression models were implemented and compared using Scikit-Learn library

### 1. Linear Regression  
- A baseline statistical model that assumes a linear relationship between features and the target variable
- Simple and interpretable
- Useful for benchmarking
- Performs best on linear patterns

### 2. Random Forest Regressor  
- An ensemble learning method based on multiple decision trees
- Reduces overfitting using bagging
- Captures non-linear relationships
- Robust to noise and feature interactions
- Strong generalization performance

### 3. Extra Trees Regressor (Extremely Randomized Trees)  
- An ensemble method similar to Random Forest with additional randomness
- Randomized split selection
- Faster training in many cases
- Lower variance compared to standard decision trees
- Effective for complex datasets

## 📈 Model Evaluation  
Models were evaluated using the following regression metrics
### 1. R² Score (Coefficient of Determination)  
- Measures how much variance of the target variable is explained by the model
- Values closer to 1 indicate better performance
### 2. RMSE (Root Mean Squared Error)
- Measures the average prediction error magnitude
- Expressed in the same unit as the target variable
- Lower values indicate better predictive accuracy

## 🏆 Results Summary  
- Linear Regression provides a strong baseline but struggles with non-linear patterns
- Random Forest shows significant performance improvement on complex relationships
- Extra Trees often achieves similar or better performance with faster training
- Ensemble models generally outperform linear models in terms of R² and RMSE

## 📌 Key Takeaways  
- Model comparison is essential in data science projects
- Ensemble methods are powerful for non-linear data
- Proper evaluation metrics provide meaningful insights
- Visualization plays a critical role in understanding data and model behavior

## 🔮 Future Improvements  
- Hyperparameter tuning (Grid Search / Random Search)
- Cross-validation for more robust evaluation
- Feature engineering
- Model persistence and deployment
- Creation of a Streamlit or Flask app

This project was developed as a Data Science and Machine Learning portfolio project, using Python and Scikit-Learn.
Check JupyterNotebook at this repository to know more about my project. 
Thanks a lot! I Hope you enjoy! 🚀













