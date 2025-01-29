
# Impact of Mortgage Rates, GDP Per Capita, and Population Growth on Housing Prices

## Project Overview
This project studies the impact of mortgage rates, GDP per capita, and population growth on housing prices in the USA from 2008 to 2022. Using Ordinary Least Squares (OLS) regression analysis, we explore how these economic factors influence housing prices.

## Data Sources
- US Federal Housing Finance Agency
- US Bureau of Economic Analysis
- Freddie Mac
- World Bank

## Data Analysis
- **Variables**: Housing Price Index (HPI), Mortgage Rates (MR), GDP per capita (GDP), Population Growth (PG)
- **Regression Model**: HPI = -1085.33 + 26.4*MR + 22.6*PG + 0.0231*GDP
- **Key Findings**:
  - Mortgage rates have a significant negative impact on housing prices.
  - Population growth has a minor positive impact on housing prices.
  - GDP per capita has a significant positive impact on housing prices.
  - The model explains 88.72% of the variation in housing prices.

## Statistical Tests
- **Jarque-Bera Normality Test**: Residuals are normally distributed.
- **Restricted Least Squares**: Mortgage rates significantly impact housing prices.
- **Multicollinearity Check**: No severe multicollinearity detected.
- **White's Heteroskedasticity Test**: No heteroskedasticity detected.
- **Ramsey RESET Test**: The model is mis-specified, suggesting non-linear relationships.
- **Durbin-Watson Test**: Autocorrelation detected, corrected using Generalized Least Squares (GLS).

## Conclusion
The analysis highlights the significant impact of mortgage rates and GDP per capita on housing prices. The corrected model using GLS provides robust estimators for accurate predictions.
