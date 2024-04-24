# Practical Assignment 2
## What drives the price of a car?

## Summary
In this analysis, I did some investigation on the provided data to identify key features that drive the price of a car.

I'm leveraging the CRISP-DM framework for the process of my analysis which have several steps from business & data understanding, data preparation, modeling, evaluation and finally deployment. 

Part of understanding the data, I also had to do some data clean-up, since there are quite a number of missing data. I dropped several columns that have a lot of missing data and not useful such as VIN, cylinder, size, etc. The rest of missing data, I filled with median for numerical data and most frequent values for categorical data.

I use data visualization (plot) in order to easily understand the data. The following shows several plot that visualize data distribution for some features of the data:

![DistYear](images/DistYear.png)
![DistPrice](images/DistPrice.png)
![DistOdometer](images/DistOdometer.png)
![Manufacturer](images/Manufacturer.png)
![CarType](images/CarType.png)
![FuelType](images/FuelType.png)
![TitleStatus](images/TitleStatus.png)
![TransmissionType](images/TransmissionType.png)

The next plots visualize the correlation between Price & Odometer and price & Year:

![PriceVsOdometer](images/PriceVsOdometer.png)
![PriceVsYear](images/PriceVsYear.png)



## Recommendation

Based on my investigation and by looking at the result of my analysis specifically the feature importance, there are several factors that drive car prices and the top four that I suggest are:
- The newer (year) the car the higher the prices and this more logical for the same car model.
- Cars with different model (or brand) may affect the price also because certain brands may be luxury brand or may be popular but hard to get.
- Cars with lower mileage (Odometer) affect higher prices.
- Certain fuel type such as Hybrid or Electric may impact the price because it can save gas cost for customers.



