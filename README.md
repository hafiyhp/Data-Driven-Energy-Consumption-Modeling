# Short-Term Energy Consumption Forecasting #

## Project Overview

Welcome to my Short-Term Electricity Consumption Forecasting project. This is a personal data exploration and forecasting project where I dive deep into a household's electricity consumption data and predict future consumption patterns. The project combines data analysis using Python and the power of Power BI for visualization, all aimed at providing actionable insights into electricity consumption.

## Table of Contents

- [Getting Started](#getting-started)
- [Data Analysis](#data-analysis)
- [Machine Learning](#machine-learning)
- [Power BI](#power-bi)
- [Results](#results)
- [License](#license)
- [Acknowledgement](#acknowledgement)

## Getting Started

- Clone this repository to your local machine to get started.
- Install the required Python libraries which are pandas, NumPy, Matplotlib scikitlearn, Jupyter Notebook, and AutoARIMA.
- Use Jupyter Notebook for in-depth data analysis and predictive modeling.
- Leverage the capabilities of Power BI for interactive dashboard creation.

## Data Analysis

Our data analysis journey begins with Pandas, NumPy, and Matplotlib:

- Examine seasonal and trend patterns in electricity consumption through time series analysis.
- Uncover correlations between variables using a correlation heat map.

But before that, we download the dataset made available by the Data Science Dojo from the following link:
(https://code.datasciencedojo.com/datasciencedojo/datasets/tree/master/Individual%20Household%20Electric%20Power%20Consumption)

## Machine Learning

We take a step into machine learning to forecast electricity consumption:

- Auto ARIMA is employed for short-term consumption predictions.
- Engineer lag features to capture time dependencies in the data.
- Develop predictive models, including Linear Regression and Random Forest Regression.
- Achieve a best Mean Squared Error (MSE) of 0.2071 with the Random Forest model.

## Power BI

Data transformation and visualization are accomplished with Power BI:

- Harness Power Query for data cleaning, transformation, and aggregation.
- Craft interactive dashboards to provide real-time insights into consumption patterns.
- Create a variety of visuals, including stacked bar charts, clustered column charts, and customized visuals for effective data communication.

## Results

The project yields tangible outcomes:

- Significant improvement in predictive accuracy with an MSE of 0.2071.
- Time-saving benefits in electricity consumption forecasting.
- Enhanced efficiency in data visualization and reporting.

## License

## Acknowledgement

I would like special thanks to Data Science Dojo for providing a publicly available dataset.

This project is open-source and is released under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to explore this project, gain insights into short-term electricity consumption patterns, and use the methodologies and techniques for your own data analysis endeavors!
