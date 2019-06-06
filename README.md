##  Problem Statement

Ascertain the important features that influence house prices both positively and negatively to ensure proper valuation. The proper valuation of houses would prevent another housing bubble from taking place.



## Executive Summary

After cleaning the data and filling in all the missing values. We focused on the visualizations where we observed specific features that were deemed to be important. Following the visualizations, we moved onto dropping some of these features as there was high collinearity and some had low variances. Next, we randomly split the train and the test results. After scaling based on the train data, we applied the scale for our test data. Then, we used GridsearchCV to find the best alpha value that we could use for the Lasso regression. Following that, the next step was to get the coefficients and to improve the model. Once, we had improved the model, we predicted the test value. To add on, the RMSE (error rate) was also calculated for reference. 


## Why is this Model important?

America had just faced a Housing bubble a decade agao and many Americans are still recovering from it. Most homes were sold at a much higher price than they should have until the housing market bubble popped. After the Housing Bubble burst many houses were sold at very low prices. Through this housing model we are creating, we are detrmining some of the most pertinent features that influence the house prices both positively and negatively. An increased awareness of these features will enable home owners to sell their houses at a competitive rate. Selling your house at the corrct price not only ensures that you are able to sell it to someone,the corect valuation of houses would also prevent another house bubble from taking place. Therefore, the proper valuation of your house would prevent another housing bubble from taking place again.