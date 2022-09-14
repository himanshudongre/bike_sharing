# bike_sharing

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


### Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

### Technologies Used:
- Python -3.10.4
- Jupyter Notebook - 1.0.0
- Pandas - v0.23.4
- Numpy - v1.5.1
- Matplotlib - v2.2.3
- Seaborn - v0.9.0
- Sklearn - v0.19.2
- Statsmodel - v0.9.0

### Conclusion
We can see that the equation of our best fitted line is:

**cnt=0.2034 + (0.2339 X yr) + (0.4917 X temp) - (0.1497 X windspeed) - (0.0483 X Jul) + (0.0723 X Sep) - (0.0450 X Sun) - (0.2847 X Light Snow) - (0.0802 X Mist Cloudy) - (0.0682 X spring) + (0.0479 X summer) + (0.0818 X winter)**

- yr,temp,Sep,summer,winter seem to have a positive impact on bike rentals
- windspeed,Jul,Sun,Light Snow,Mist Cloudy,spring seem to have a negative impact on bike rentals
- It appears that higher temeratures and good weather are primary factors that leads to high bike rentals.
- To improve bike rentals in future company can experiment with increased advertisements and offers during the month of September and during summer.
- R2score on the test set is 0.8057616301094372
