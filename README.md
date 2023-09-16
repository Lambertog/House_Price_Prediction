Prediciting prices of house in an area in the United States of America given the size of the land,distance from the city centre,and crime rate in the region.This is a predictive analyses using/comparing different regression analysis techniques. A simple linear regression model was used to predict prices with considering only the area of the land.

SECOND PART.
This section has a mixture of regularization of the analysis on house prediction but with more variables.
The first section was on Multiple linear regression considering multiple correlation of variables while the other part was with added variables (three more columns) of different cities.
We did the analysis both by checking for multi collinearity and the two most common regularization techniques(Ridge and Lasso regression).
All values are in USD Million.

We also decided to explore the use of Random forest regression in a case like this for the sake of knowledge with different dataset. When this data was loaded and analysed with ridged and lasso, only lasso was able to show variation closed to that of random forest. However, the difference between the predicted and actual prices,was wider than that of random forest. Hence, Lasso regression is also reliable for this dataset.
