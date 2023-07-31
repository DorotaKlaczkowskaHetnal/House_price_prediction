# House_price_prediction

I downloaded the data from the follwing link https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot

The data pertains to properties in the city of Melbourne. It contains many atributes like: number of rooms, price, date of sale, land size or latitude and longitude.

It is commonly known that location of a property is one of the most important factors which influence the price.
Melbourne is shaped like an inverted C, located on the shores of Port Phillip Bay in the Indian Ocean. Therefore, property prices will fluctuate depending 
on the proximity to the city center as well as the distance from the bay. This means that property prices are not linearly dependent on the latitude 
and longitude, so I cannot use a linear regression model to predict property prices. Thus, I tested Decision Tree Regressor and Random Forest.
