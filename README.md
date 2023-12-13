# **Project Name**
> * Assignment : BoomBike sales case study
> * Team Member Detail: Name: Lokesh Gaddam
> * Date : 12 Dec 2023


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)



## **General Information**
> ### **Problem Statement**

> - A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

> - A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

> - In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

> - They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. 

>The company wants to know:
> * Which variables are significant in predicting the demand for shared bikes
> * How well those variables describe the bike demands

>  Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

### **Business Goal of the Assignment**
> You are required to model the demand for shared bikes with the available independent variables. 
> It will be used by the management to understand how exactly the demands vary with different features. 
> They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

> The data set that is used for this purpose is day.csv
### **Below are the steps to be followed**
> 1. Extracting the data , undersanding and visualizaing the data to make first level inferences 
> 2. Preparation of the data for model training which includes train-test split and rescaling based on the insights 
> 3. Training the model 
> 4. Perform Residual analysis 
> 5. FInally prediction and evaluation of the test set 

## **Conclusions**

**Final results and comparision between Train model and test :**
    
> - Train R^2 : 0.833
> - Train Adj R^2 : 0.829
> - Test R^2 : 0.813
> - Test Adj R^2 : 0.798
> - Different in R^2 between train and test : ~ 2%m
> - Difference in Adj R^2 between train and test :  ~3% which is less than 5%
    
**In summary, considering the above points , this seems to be final acceptable model**

> **Final summary analysing the above model, the comapany should focus on the following features:**

> **1.Expanding Business During Spring**
> - Spring is considered a good time to expand business, likely due to pleasant weather and potentially increased consumer activity. The company could focus on launching new offers or promotions during this season.

> **2. Expanding Business During September:**
> - September is also highlighted as a key period for business expansion, possibly because of favorable market conditions or historical trends. It would be beneficial for the company to concentrate efforts on growth initiatives during this time.

> **3. Anticipated Boom in Users Post-Normalization:**
> - The expectation is that there will be a significant increase in the number of users once the situation returns to normal, especially when compared to the pre-pandemic year 2019. This suggests an optimistic outlook for the company's future.

> **4. Utilizing Light Snow or Rain Periods for Bike Servicing:**
> - During periods of light snow or rain when there may be fewer bookings, the company could use this time to service bikes without a substantial impact on business operations. This proactive approach ensures that the bikes are well-maintained for peak demand periods.

> **5. Strategic Offers and Advertising:**
> - When the situation returns to normal, the company should consider launching new offers and advertising during the pleasant weather of spring. Additionally, September is identified as a peak business period, so targeted advertising efforts should be in place during that month.

>> - In summary, your proposed strategy involves a combination of seasonal planning, weather-based operational adjustments, and strategic marketing efforts during key months. It's a well-rounded approach that takes into account both internal factors (bike servicing) and external factors (weather, market conditions). However, the success of this strategy would also depend on the specific industry, market dynamics, and the company's capabilities. It may be beneficial to continuously monitor and adapt the strategy based on real-time data and market feedback.


 **Significant variables to predict the demand for shared bikes**

   > - holiday
   > - temp
   > - humidity
   > - windspeed
   > - Season
   > - months(Dec, Jul, Mar,m Nov,Sep)
   > - Year (2019)
   > - Sunday
   > - weathersit( Light Snow, Mist + Cloudy)

## **Technologies Used**
> - Jupyter note book v2.5.0
> - python3
> - Libraries: numpy, pandas, seaborn, sklearn, statsmodels