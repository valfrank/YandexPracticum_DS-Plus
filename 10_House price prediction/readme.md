# House price prediction

## Project description

In a project, we need to train a linear regression model on California housing data in 1990. 

**Aim** - Based on the data, predict the median cost of a house in a residential area - median_house_value. Use the RMSE, MAE, and R2 metrics to evaluate the quality of a model.

## Data
- longitude;
- latitude;
- housing_median_age - the average age of the residents of the residential area;
- total_rooms - the total number of rooms in the houses of the residential area;
- total_bedrooms - the total number of bedrooms in the houses of the residential area;
- population - the number of people who live in a residential area;
- households - the number of households in the residential area;
- median_income - average income of residents of a residential area;
- median_house_value - median cost of a house in a residential area;
- ocean_proximity - proximity to the ocean.

## Resume
- Pre-processing and exploratory data analysis
- Build two linear regression models on different datasets:
		+ using all the data from the file;
		+ using only numerical variables, excluding categorical ones.
- The model trained only on numerical data showed higher values of the main metrics RMSE and MAE		

## Skills and tools 
- python
- pandas
- mathplotlib
- seaborn
- sklearn
- pipeline
- GridSearchCV
- SMOTE
- sweetviz
