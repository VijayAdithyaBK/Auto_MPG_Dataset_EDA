# Auto MPG EDA

## Overview
This project involves an exploratory data analysis (EDA) of the Auto_MPG dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/auto+mpg), which contains technical specifications of cars, originally sourced from the UCI Machine Learning Repository. The analysis focuses on understanding city-cycle fuel consumption in miles per gallon (MPG) in relation to various attributes.

## Dataset Description
The dataset consists of 398 records and 9 columns, which include:

- **mpg**: Miles per gallon (continuous variable)
- **cylinders**: Number of engine cylinders (multi-valued discrete variable)
- **displacement**: Engine displacement (continuous variable)
- **horsepower**: Engine horsepower (continuous variable)
- **weight**: Car weight (continuous variable)
- **acceleration**: Acceleration (continuous variable)
- **model year**: Year of car release (1970 to 1982) (multi-valued discrete variable)
- **origin**: Car manufacturing place (1 -> USA, 2 -> Europe, 3 -> Asia) (multi-valued discrete variable)
- **car name**: Unique car model name

## Findings and Insights
1. **MPG Trends**: Notable increase in MPG over the years with Asian cars leading in efficiency.
2. **Cylinders vs. MPG**: Higher cylinder counts correlate with lower MPG.
3. **Origin Insights**: USA produces the most cars but has lower MPG compared to Europe and Asia.

## Conclusion
This EDA provides valuable insights into car specifications and their relationship with fuel efficiency. The findings can guide future automotive designs towards improved fuel economy.
