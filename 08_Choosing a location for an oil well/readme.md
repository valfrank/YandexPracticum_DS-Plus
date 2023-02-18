# Choosing a location for an oil well

## Project description

Only linear regression is suitable for training the model.

During the exploration of the region, 500 points are explored, from which, using machine learning, the best 200 are selected for development.

The budget for the development of wells in the region is 10 billion rubles.

At current prices, one barrel of raw materials brings 450 rubles of income. The income from each unit of the product is 450 thousand rubles, since the volume is indicated in thousands of barrels.

After assessing the risks, you need to leave only those regions in which the probability of losses is less than 2.5%. Among them, choose the region with the highest average profit.

**Aim** - Build a model to determine the region where mining will bring the most profit. Analyze possible profits and risks using the Bootstrap technique.

## Data
Exploration data from three regions
- id is the unique identifier of the well;
- f0, f1, f2 - three signs of each region;
- product is the volume of reserves in the well (thousand barrels).

## Resume
- Three models for different regions were trained to predict oil volumes. 
- Profit, interval and risks were calculated for three regions. 
- Based on RMSE and risks, we decided to use third region data to train future model.

## Skills and tools 
- python
- pandas
- mathplotlib
- sklearn
- Bootstrap
