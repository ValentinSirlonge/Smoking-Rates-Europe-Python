# Smoking Rates in European Countries
This repository contains a Python project analyzing smoking rates in European countries and the impact of anti-smoking policies and support programs on smoking prevalence. The analysis uses publicly available datasets and applies statistical and machine learning techniques.

<p align="center">
  <img src="https://www.leparisien.fr/resizer/e04v-yP_LR272i1pPZE3Nu3R68Y=/932x582/cloudfront-eu-central-1.images.arcpublishing.com/leparisien/UUZ32DO5VBDZTH35NXQKYRWCC4.jpg" 
       alt="Smoking Rates in European Countries" 
       width="400"/>
</p>


## Project Overview
- **Hypothesis**: European countries with strict anti-smoking policies and strong support programs to quit smoking have significantly lower smoking rates.
- **Datasets Used**:
  - Share of adult smokers
  - Share of male smokers
  - Share of female smokers
  - Enforcement of bans on tobacco advertising
  - Support to quit smoking
- **Scope**: Focused on European countries in 2020.


## Features and Analysis
1. **Data Cleaning**:
   - Filtered datasets for European countries and the year 2020.
   - Retained key variables: country, total smokers, male smokers, female smokers, advertising bans, and support programs.

2. **Exploratory Data Analysis**:
   - Generated descriptive statistics and visualizations to explore smoking patterns by gender and region.

3. **Statistical Tests**:
   - Conducted a t-test to compare male and female smoking rates.

4. **Regression Analysis**:
   - Analyzed the relationship between anti-smoking policies and smoking rates.
   - Built a linear regression model to predict smoking rates based on gender-specific data.

5. **Key Findings**:
   - Statistically significant difference in smoking rates between men and women (p-value: 0.00000039).
   - A weak positive correlation between male and female smoking rates.
   - Accurate prediction of smoking rates with a Mean Squared Error (MSE) of 0.00055.


## Libraries Used
To analyze the data, I used the following libraries:
- **pandas**: Data manipulation and analysis.
- **numpy**: Numerical computations.
- **seaborn**: Data visualization.
- **matplotlib**: Plotting and charting.
- **scipy**: Statistical testing.
- **sklearn**: Machine learning and regression modeling.


## Presentation
A PowerPoint presentation summarizing the findings is included in this repository:
SmokingRatesAnalysis.pptx
