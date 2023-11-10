# Capstone Project: Real Estate Transaction Analysis in Japan
Author: Aditi Namboodiripad

Date: 11/10/2023

Contact: chittooradi@gmail.com


## Project Overview

### Problem Area
The Capstone project aims to analyze real estate transaction data in Japan, covering the period from 2005 to 2019. This dataset was surveyed by the Ministry of Land, Infrastructure, Transport, and Tourism of Japan (MLIT). The primary goal is to gain insights into the trends and factors influencing real estate prices in Japan over this 15-year period. For now I will be dealing with Pre-owned condos,etc. real-estate type.

### Those Affected
The analysis of this dataset can benefit various stakeholders, including real estate investors, developers, city planners, and anyone interested in understanding the dynamics of the Japanese real estate market. By identifying trends and factors affecting property prices, this analysis can provide valuable information for making informed decisions in the real estate sector.

### Proposed Data Science Solution
This capstone will mainly focus on the prediction of Trade prices of real estate. The proposed data science solution involves the following key components:

1. Data Exploration: Exploring and understanding the dataset, including data cleaning, feature selection, and preprocessing.

2. Descriptive Analysis: Analyzing basic statistics, distributions, and trends in real estate transaction prices, regions, and more.

3. Time period Analysis: Investigating how real estate prices have evolved over time, identifying yearly and quarterly trends.

4. Spatial Analysis: Examining prefecture level variations in property prices, identifying high-performing prefectures, and assessing whether there's a difference in property prices between Tokyo (the capital) and other areas.

5. Factors Affecting Prices: Investigating the factors influencing property prices, such as property type, proximity to transportation, building structure, land shape, and more.

6. Predictive Modeling: Developing predictive models to estimate future property prices based on historical data and identified factors.
   
### Further for predictions different models can be used:

1.Regression Models like Linear regression,Decision Trees, Lasso, Ridge, or Elastic Net to predict property prices based on selected features.

2. Gradient Boosting: XGBoost, LightGBM, or CatBoost for improving predictive accuracy.

3. Neural Networks: Deep learning models such as neural networks for modeling complex relationships.

4. Evaluation Metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), or Root Mean Squared Error (RMSE) to assess model performance.
 

May need to experiment with multiple models and evaluate their performance to determine the best approach for each component.

### Impact of the Solution
The analysis of this real estate dataset can have several potential impacts:

- **Market Insights:** It can provide valuable insights into how the Japanese real estate market has evolved, helping stakeholders make informed investment decisions.
- **Investment Decisions:** Investors can use the predictive models to estimate future property prices and make data-driven investment decisions.
- **Regional Comparisons:** Understanding price variations between Tokyo and other prefectures areas can guide property buyers and sellers.

Japan saw its population peak in 2008 and is aging quickly. The old-age dependency ratiov was 47 in 2019. As aggregate housing supply exceeds housing demand, the national vacancy rate reached 13.6% for all housing types and 18.5% for rental housing in 2018. Wealthy individuals motivated by tax advantages supply small apartment units, but do not lower rents to fill vacant units because low-rent tenants will sit in the apartment for an extended period. At the same time, owners try to avoid renting to families because of low turnover.

5% improvement in predicting trade prices can contribute to more affordable housing options for buyers.
Market efficiency, it might lead to a 10% increase in the overall effectiveness of property transactions.

### Dataset Description
The dataset consists of the following fields:

- **Type:** Real Estate Type (e.g., Residential Land, Agricultural Land, Condominiums).
- **Region:** Characteristics of surrounding areas (e.g., Residential Area, Commercial Area).
- **MunicipalityCode:** City code of Japan.
- **Prefecture:** Prefecture name of Japan.
- **Municipality:** City name.
- **DistrictName:** District name.
- **NearestStation:** Nearest station name.
- **TimeToNearestStation:** Time to the nearest station (in minutes).
- **TradePrice:** Transaction prices in Japanese Yen.
- **FloorPlan:** Property floor plan (e.g., 3LDK, 2DK).
- **Area:** Surveyed area in square meters.
- **UnitPrice:** Unit Land Price (Yen) per square meter.
- **PricePerTsubo:** Unit Land Price (Yen) per Tsubo.
- **Frontage:** Frontage in meters.
- **BuildingYear:** Construction year of the building.
- **PrewarBuilding:** Buildings built before 1945.
- **Structure:** Building structure (e.g., Steel frame reinforced concrete, Wooden).
- **Use:** Current property usage (e.g., House, Office, Factory).
- **Purpose:** Purpose of future use (e.g., House, Shop, Office).
- **Direction:** Frontage road direction.
- **Classification:** Frontage road classification (e.g., City Road, National Highway).
- **Breadth:** Frontage road breadth in meters.
- **CityPlanning:** Use districts designated by the City Planning Act.
- **CoverageRatio:** Maximum Building Coverage Ratio (%).
- **FloorAreaRatio:** Maximum Floor-area Ratio (%).
- **Period:** Time of transaction.
- **Year:** Time of transaction year.
- **Quarter:** Time of transaction year-quarter.
- **Renovation:** Renovation status.
- **Remarks:** Additional notes and remarks.

## Flowchart
1. **Data Collection:**
   - Retrieve the dataset 
   
2. **Data Preprocessing:**
   - Handle missing values.
   - Address data quality issues.
   - Perform feature engineering.
   
3. **Exploratory Data Analysis:**
   - Analyze distributions of variables.
   - Visualize patterns and correlations.
   - Formulate initial questions for further investigation.
4. **Baseline Modeling :**
   - Linear regression and random forest models.
   - Evaluation of model performance using RMSE and R-squared.
   - Interpret model coefficients for insights.

5. **Advanced Modeling (Sprint 3):**
   - Cross validation
   - Fine-tune hyperparameters.
   - Advanced models
- Ridge and Lasso Regression: Implement Ridge and Lasso regression to handle potential multicollinearity and feature selection.
- Gradient Boosting Regressor:Try models like Gradient Boosting Regressor, which can capture complex relationships in the data.
- Support Vector Machines (SVM): Experiment with Support Vector Machines for regression (SVR) to capture non-linear patterns.
- Neural Networks:Explore neural networks for regression using frameworks like TensorFlow or PyTorch.

6. **Business Implications and Future Work:**
   - Discuss the practical implications of model performance.
   - Outline limitations and potential improvements.
   - Propose next steps for model refinement.
   - Productizing work

## Acknowledgements and Source
**Source:** https://www.kaggle.com/datasets/nishiodens/japan-real-estate-transaction-prices

This dataset is a slightly cleaned-up version of the one published by MLIT.
