# Car price prediction

## Project Description 
Service for selling used cars is developing an application to attract new customers.

**Aim** - build a model that can determine the cost of a car. 
The RMSE value must be less than 2500.

*Criteria that are important to the customer:*
- quality of prediction;
- model training time;
- model prediction time.

## Data
We have data on the technical characteristics, equipment and prices of other vehicles.
*Features*
- DateCrawled - date of downloading the questionnaire from the database
- VehicleType - type of car body
- RegistrationYear — year of vehicle registration
- Gearbox - type of gearbox
- Power - power (hp)
- Model - car model
- Kilometer - mileage (km)
- RegistrationMonth - month of car registration
- FuelType — type of fuel
- Brand - car brand
- Repaired - was the car under repair or not
- DateCreated - date of creation of the questionnaire
- NumberOfPictures - the number of photos of the car
- PostalCode - postal code of the owner of the profile (user)
- LastSeen - date of last user activity

*Target*
- Price - price (euro)

## Resume
- Data loaded and pre-processed.
- Trained 5 different models on cross-validation
- Comparison of models is executed.
- The best model was selected based on the results of the RMSE metric and training time.

## Skills and tools
- python
- pandas
- numpy
- matplotlib
- seaborn
- sweetviz
- sklearn
- Gradient Boosting
- lightgbm
- xgboost
- scipy
