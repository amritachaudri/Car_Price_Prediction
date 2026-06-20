# Car Price Prediction

## Project Overview
This project analyzes the determinants of car prices in the American automobile market using statistical modeling and feature selection techniques. The analysis is based on the notebook **Prediction of Car Prices.ipynb**, which applies regression modeling to identify the most significant predictors of car pricing.

## Key Predictors of Car Price
The final regression model (**Model 6**) highlights the following variables as the most influential:

- **Engine Size** (`enginesize`): Strongly correlated with performance and price.
- **Car Width** (`carwidth`): Reflects vehicle class, interior space, and premium positioning.
- **Rotary Engine Type** (`enginetype_rotor`): A niche mechanical feature with pricing impact.
- **Rear Engine Location** (`enginelocation_rear`): Common in high-performance sports cars.
- **Brand Premium** (`car_company_bmw`, `car_company_renault`): Demonstrates the strong role of brand identity in pricing.

All selected variables show low multicollinearity, with the highest Variance Inflation Factor (VIF) being **3.01** for `enginesize` (well below the threshold of 5).

## Model Performance
- **Training Accuracy**: Adjusted \(R^2\) ≈ **99.2%** (excellent fit).
- **Testing Accuracy**: \(R^2\) ≈ **89.97%** (strong generalization on unseen data).

This indicates the model is both robust and reliable in predicting car prices.

## Strategic Insights
- **Engineering Focus**: Larger engine capacity and optimized car width are critical for achieving premium price levels.
- **Competitive Positioning**: Brands like BMW set benchmarks in pricing dynamics. Geely Auto and other entrants must align their strategies accordingly.
- **Market Differentiation**: Unique mechanical features (e.g., rotary engines, rear engine placement) can carve out niche premium segments.

## How to Use
1. Open the notebook `Prediction of Car Prices.ipynb`.
2. Run the cells sequentially to reproduce the analysis.
3. Review the regression outputs and feature importance for insights.
