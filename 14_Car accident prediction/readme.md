# Car accident prediction

## Project description

*Main aims:* to create a model that could assess the risk of an accident along a selected route. Risk is the probability of an accident with any damage to the vehicle. Once a driver has booked a car, got behind the wheel, and chosen a route, the system must assess the level of risk. If the risk level is high, the driver will see a warning and route recommendations.

For the model, select the type - only car.

Select cases where the accident resulted in any damage to the vehicle, except for the type of SCRATCH (scratch).

For modeling, limit data for 2012 - they are the most recent.

A prerequisite is to take into account the age factor of the car.

## Resume
A model has been built to predict whether a driver will be at fault in an accident based on driver condition, weather conditions, road conditions and lighting conditions.
AdaBoost Classifier model was used with F1 Score 0.54 Precision 0.73 Recall 0.43. The most significant features are: the travel time, the age of the car and the sobriety of the driver.


## Skills and tools
- python
- sql
- pandas
- seaborn
- sweetviz
- sklearn
- CatBoost
- AdaBoost
- phik correlation
