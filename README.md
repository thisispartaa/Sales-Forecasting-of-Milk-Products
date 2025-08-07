**Sales Forecasting of Milk Products**

[Report Link](https://drive.google.com/file/d/1e2BuZ2chgqAWBSmFg4J9IORfrTdnUvpL/view?usp=drive_link)

**Overview**

This project analyzes grocery retail data related to milk and milk-based products to identify factors influencing dollar sales and brand preferences. It utilizes statistical modeling to understand consumer behavior, the effect of marketing factors like display and features, and how different packaging or product attributes impact sales.

**Objectives**
- Analyze the impact of product features (like flavor, packaging, processing) on dollar sales.
- Identify consumer preferences for top milk brands.
- Forecast milk product sales using regression models.
- Provide actionable insights for business decisions in retail and marketing.

**Key Findings**
- Display and promotions significantly increase product sales, with display alone contributing to a ~$515 increase.
- Private Label is the highest revenue-generating brand, followed by Silk, Nestle Nesquik, and Lactaid100.
- Packaging type and flavor greatly influence purchase behavior: plastic jugs and white-flavored milk lead to higher sales.
- Price reductions and feature displays also positively influence consumer purchasing decisions.
- Product type and fat content show varied influence: regular and reduced-fat milk perform better than buttermilk or low-fat options.

**Methodology**
- Data preparation and cleaning: Over 4 million records sampled to ~1 million for analysis.
- Dummy variables created for multi-category features.
- Correlation analysis to understand inter-variable relationships.
- Multiple Linear Regression to predict dollar sales.
- Logistic Regression to evaluate brand preference likelihoods.
- Heteroscedasticity and multicollinearity tests conducted to validate regression models.

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
