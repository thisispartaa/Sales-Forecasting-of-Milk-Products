**Sales Forecasting of Milk Products**

[Report Link](https://drive.google.com/file/d/1e2BuZ2chgqAWBSmFg4J9IORfrTdnUvpL/view?usp=drive_link)

**Overview**

This project focuses on analyzing milk product sales data from grocery stores to understand consumer behavior, brand influence, and sales drivers. Using statistical modeling and retail data, the goal is to generate insights that inform marketing strategies and sales forecasting. Developed a predictive model in SAS for forecasting milk product sales, achieving an accuracy of 83%.

**Objectives**
- Analyze the impact of product features (like flavor, packaging, processing) on dollar sales.
- Identify consumer preferences for top milk brands.
- Forecast milk product sales using regression models.
- Provide actionable insights for business decisions in retail and marketing.

**Key Findings**
- Identified store features, display, and discount as key drivers of brand revenue, leading to a projected 12% increase in sales.
- Packaging type, flavor, and processing method are strongly correlated with sales volumes.
- Private Label emerged as the top-performing brand, followed by Silk and Nestle Nesquik.
- Carton and plastic bottle packaging types underperform compared to plastic jugs.

**Methodology**
- Cleaned and sampled ~1 million records from a larger dataset of 4M+ observations.
- Created dummy variables for categorical features (brands, flavors, package types).
- Performed correlation and multicollinearity checks to validate input features.
- Built a Multiple Linear Regression model to forecast dollar sales.
- Used a Logistic Regression model to assess brand preference likelihood.
- Conducted statistical validation using heteroscedasticity and VIF tests.

**Tools and Technologies**
- SAS: Data preparation, statistical modeling, PROC CORR, PROC LOGISTIC
- Excel: Preliminary data checks
- Statistical Methods:
  - Multicollinearity (VIF)
  - White’s Test for heteroscedasticity
  - Cumulative Logit Model for brand preference
  - Multiple Linear Regression for sales forecasting

**Conclusion**
The study reveals that marketing levers (feature, display, and promotions) and product characteristics like flavor, packaging, and brand significantly influence milk sales in retail settings. The findings can aid grocery chains and milk brands in optimizing their product placement, promotional strategies, and inventory decisions to maximize revenue.

**Future Prospects**
- Build predictive ML models using XGBoost/Random Forest for better performance.
- Include seasonal trends and external market factors (e.g., holidays, weather).
- Visualization dashboard for interactive analysis (using Power BI or Tableau).
