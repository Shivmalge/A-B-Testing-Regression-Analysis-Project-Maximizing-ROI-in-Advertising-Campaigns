# A/B Testing & Regression Analysis: Maximizing ROI in Ad Campaigns
Applied hypothesis testing and regression modeling to assess and optimize the performance of Facebook and AdWords ad campaigns. Delivered actionable insights to maximize conversions and improve ROI through data-driven marketing strategies.

# 📊 Ad Campaign Effectiveness Analysis: Facebook vs. AdWords

## 🌟 Project Summary
This project investigates and compares the performance of Facebook and AdWords advertising platforms throughout 2019. The objective is to identify the platform that delivers superior results in terms of clicks, conversions, and cost-efficiency—ultimately helping to improve ROI and drive smarter marketing decisions.

## ❓ Problem Statement
As a data-driven marketing agency, improving the return on investment (ROI) for advertising campaigns is a key priority. By analyzing campaign data from both Facebook and AdWords, the goal was to pinpoint the better-performing platform and optimize future ad spending accordingly.
#### Key Question:
➡️ Which advertising platform delivers higher conversions, better engagement, and improved cost-efficiency?

## 🛠️ Tools & Libraries
- Data Processing: Pandas, NumPy
- Visualization: Matplotlib, Seaborn
- Statistical Testing: SciPy, Statsmodels
- Predictive Modeling: Scikit-learn (Linear Regression)
- Additional Analysis: Cointegration testing, warnings management

## 🗂️ Dataset Overview
The dataset captures daily advertising performance metrics for the year 2019, comprising 365 records for both Facebook and AdWords campaigns. Key fields include:

- Date: The date of the campaign run.
- Ad Views: Number of times the ad was displayed.
- Ad Clicks: Number of user clicks on the ad.
- Ad Conversions: Number of completed actions (conversions) from the ad.
- Cost per Ad: Campaign cost for the day.
- Click-Through Rate (CTR): Clicks as a percentage of views.
- Conversion Rate: Conversions as a percentage of clicks.
- Cost per Click (CPC): Average cost per user click.

## 🔍 Methodology & Process
### 1. Data Preprocessing
- Parsed the Date column into datetime objects for time-series analysis.
- Cleaned and converted financial and percentage columns into numeric values.
- Verified data types for smooth computation and analysis.

### 2. Exploratory Data Analysis (EDA)
- Trend Analysis: Visualized distributions of clicks and conversions using histograms. Facebook consistently showed higher conversion rates.
- Categorical Insights: Grouped conversion rates into ranges, highlighting Facebook’s dominance in high-conversion days.
- Correlation Study: Found a strong correlation (0.87) between clicks and conversions on Facebook, versus a moderate correlation (0.45) for AdWords.

### 3. Statistical Hypothesis Testing
- Hypothesis: Facebook ads lead to significantly more conversions than AdWords.
- Conducted an independent T-test:
    - Facebook mean conversions: 11.74
    - AdWords mean conversions: 5.98
    - T-statistic: 32.88, p-value: 9.35e-134

- Result: Strong evidence supports the alternative hypothesis—Facebook outperforms AdWords in conversions.

### 4. Regression Analysis
- Built a Linear Regression model predicting Facebook conversions based on ad clicks.
- Model Results:
  - R² Score: 76.35%
  - Low mean squared error (MSE), suggesting a strong fit.
- Example Predictions:
  - 50 clicks → ~10 conversions
  - 80 clicks → ~16 conversions

### 5. Time-Based Insights
- Weekly Patterns: Mondays and Tuesdays had the highest conversions.
- Monthly Insights: Conversion dips were observed in February and May; November saw peak performance.

### 6. Cost Efficiency Analysis
- Analyzed monthly Cost Per Conversion (CPC).
- Identified May and November as months with the lowest CPC—ideal periods for ad spend.

### 7. Cointegration Analysis
- Conducted cointegration testing between ad spend and conversions.
- Detected a statistically significant long-term equilibrium, indicating that changes in ad budget consistently affect conversions over time.

## 🔑 Key Insights
- ✔️ Facebook significantly outperforms AdWords in driving conversions and maximizing ROI.
- ✔️ Strong click-to-conversion correlation on Facebook highlights its campaign efficiency.
- ✔️ Time-based trends suggest running more ads on Mondays and in November for better performance.
- ✔️ Regression analysis enables accurate conversion predictions based on planned ad clicks.
- ✔️ May and November offer cost-effective advertising windows.
- ✔️ Cointegration analysis validates that increased ad spend positively impacts conversions long-term.

## 🚀 Business Impact
- Prioritize Facebook for future ad campaigns to maximize ROI.
- Reallocate budgets during low-cost, high-conversion periods.
- Use predictive models to estimate campaign outcomes and optimize targeting.
- Strategically time ad placements based on weekly and monthly trends.

## ✅ Conclusion
By combining statistical hypothesis testing, exploratory analysis, and machine learning models, this project empowers marketers to make data-backed decisions for optimizing advertising strategies. The insights clearly show Facebook as the preferred platform for higher conversions and better cost-efficiency, helping guide future campaign planning and execution.

Project By - Shivsharan Malage

[Github](https://github.com/Shivmalge)

[Linkedin](https://www.linkedin.com/in/shivsharan-malage-99802a230/)
