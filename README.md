# King County Regression

**Authors**: Dave Brown, Michael Tiernan

## Problem

Mission:  Use regression modeling to analyze housing prices in the county.

Steps:
1. Research for data and develop a plan.
2. Clean the data
3. Reorganize the dataset
4. Check for multicollinieary and other issues
5. Make adjustments to the data accordingly
6. Run the regression model
7. Present findings

## Methodology

For this project, we were given the kc_house_data.csv. THe dataset countained information about houses, ranging from the year built, to the number of bedrooms and bathrooms, to the total square feet of living space of the closest 15 neighbors.

After taking care any possible duplicate and null values, we eliminated any possible outliers. Then we checked for any multicollinearity issues. Next, we made sure to eliminate any columns that were not adequate predictors, and normalized the data. Finally, we ran simple linear and multilinear regression models until we found an acceptable result.

## Housing Valuation



### Findings


## Geopandas


### Findings


## Recommendations


## For More Information

Please review our full analysis in [our Jupyter Notebook]() or our [presentation]().

For any additional questions, please contact Dave Brown: davebrown271@gmail.com,


## Repository Structure
#### Main Page
    ├── README.md                              <- The top-level README for reviewers of this project
    ├── housing_exploration.ipynb              <- The data analysis for the housing valuation
    ├── housing_model.ipynb                    <- The linear regression modelling for the housing valuation
    ├──
    ├──
    ├── data
        ├── kc_house_data.csv                  <- The original dataset used for this project
        ├── column_names.md                    <- Descriptions of the columns in the kc housing dataset
        ├── housing_aspects.csv                <- The updated dataset used for the housing valuation
