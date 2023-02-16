# Tariff recommendation

## Project description

Many customers use archival tariffs. Mobile operator want to build a system that can analyze customer behavior and offer users a new tariff: "Smart" or "Ultra".

**Aim** - build the model for the classification problem with the largest possible accuracy value (min 0.75).

## Data

**Information about the behavior of one user per month**
- calls — number of calls,
- minutes — total duration of calls in minutes,
- messages — number of sms messages,
- mb_used - Internet traffic used in Mb,
- is_ultra - what tariff did you use during the month ("Ultra" - 1, "Smart" - 0).


## Resume
- Examine the data file.
- Divide the data into three samples: training, validation and test.
- Explore three classification models: Decision Tree, Random Forest and Logistic Regression.
- Evaluate the accuracy of the trained model.


## Skills and tools 
- python
- pandas
- sklearn
- Linear models
- Desicion Tree, Random Forest
