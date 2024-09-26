# California-housing-problem

## Data source : [Kaggle California Housing Prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices/data)

## Brief summary about dataset

#### 'Hands-On Machine learning with Scikit-Learn and TensorFlow', a recent book by Aurélien Géron, uses this dataset in its second chapter. Because it contains a manageable set of variables, is just the right amount of toy-like and complicated, and only necessitates basic data cleaning, it's a great starting point for developing machine learning algorithms.

#### The data contains information from the 1990 California census. So although it may not help you with predicting current housing prices like the Zillow Zestimate dataset, it does provide an accessible introductory dataset for teaching people about the basics of machine learning.

## Goal of the report

### The primary goal of this report is to forecast the median house value based on three independent values namely the population, median income and the number of households, the report is to design and asses three univerate linear regression models that predict median house value. We are looking to explain each independent's variables ability to explain and predict the median house value by working on a model for each. The conclusion will contain our findings and which model predict most accurately


## List of Columns

1. **longitude**: A measure of how far west a house is; a higher value is farther west.
2. **latitude**: A measure of how far north a house is; a higher value is farther north.
3. **housingMedianAge**: Median age of a house within a block; a lower number is a newer building.
4. **totalRooms**: Total number of rooms within a block.
5. **totalBedrooms**: Total number of bedrooms within a block.
6. **population**: Total number of people residing within a block.
7. **households**: Total number of households, a group of people residing within a home unit, for a block.
8. **medianIncome**: Median income for households within a block of houses (measured in tens of thousands of US Dollars).
9. **medianHouseValue**: Median house value for households within a block (measured in US Dollars).
10. **oceanProximity**: Location of the house with respect to the ocean/sea.



## Acknowledgements

This data was initially featured in the following paper:

**Pace, R. Kelley, and Ronald Barry.**  
"Sparse spatial autoregressions."  
*Statistics & Probability Letters*, 33.3 (1997): 291-297.

I encountered this dataset in *Hands-On Machine Learning with Scikit-Learn and TensorFlow* by **Aurélien Géron**.  
Aurélien Géron wrote:  
"This dataset is a modified version of the California Housing dataset available from Luís Torgo's page (University of Porto)." 
