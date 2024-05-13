# Crime Analysis in Louisville, KY

## Overview

This project undertakes a comprehensive analysis and predictive modeling of serious and violent crimes in Louisville, Kentucky. By integrating crime incident reports, police division data, and weather information, the study aims to identify key factors influencing crime rates and the impact of environmental conditions like temperature. A novel feature related to holidays is also introduced to assess its correlation with crime occurrences.

## Project Goals

- **Define and Categorize Crimes**: Classify crimes into serious and violent categories for targeted analysis.
- **Focus Analysis**: Concentrate on a specific police district to understand localized crime patterns.
- **Predictive Modeling**: Use linear regression and other statistical methods to predict crime rates, incorporating external factors such as weather and holidays.
- **Temporal Analysis**: Employ time series forecasting to understand and predict crime trends.

## Data Sources

- **Crime Incident Reports**: Detailed records from the Louisville Metro Police Department. [View Dataset](https://data.louisvilleky.gov/datasets/e38e1552bd2d4d77ba6e4b371128311f/explore)
- **Weather Data**: Sourced from Visual Crossing Weather Data Services. [View Dataset](https://www.visualcrossing.com/weather/weather-data-services)
- **Holiday Data**: Analysis includes holidays as a variable to study its impact on crime rates.

## Data Analysis and Predictive Modeling

### Classification of Crime

We classify crime data into 'Serious' and 'Violent' categories, enabling focused analysis and predictive modeling. Binary variables for each category aid in machine learning classification tasks.

### Modeling Techniques

1. **Linear Regression Models**:
   - Predict serious and violent crime counts using weather variables such as temperature and humidity.
   - Analyze how external factors like public holidays impact crime rates.

2. **Random Forest Regression**:
   - Forecast total crime counts using a combination of weather conditions and crime-related features.

3. **Time Series Analysis (ARIMA)**:
   - Predict future crime rates using historical data and external regressors like temperature.

### Exploratory Data Analysis (EDA)

- Analyze crime distribution by time and location to identify patterns.
- Assess the impact of weather conditions and holidays on crime occurrences.

## Visualization

- **Correlation Plots**: Understand the relationship between different variables and crime occurrences.
- **Time Series Decomposition and Prediction Plots**: Visualize trends, seasonality, and predictions for crime rates.

## Installation and Usage

1. **Setup**: Clone the repository and install required R packages.
2. **Data Loading**: Load the datasets from the provided links.
3. **Run Analysis**: Execute the R Markdown script to reproduce the analysis and visualizations.

## Contributing

Contributions to enhance the analysis or predictive models are welcome. Please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.


![image](https://github.com/vinayvaida27/Crime-Analysis-in-Louisville-KY/assets/115647297/c502484d-51d9-4c5f-8372-9ad74a156b90)

