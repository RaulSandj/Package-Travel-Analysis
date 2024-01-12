# Package Travel Analysis
## About Dataset
###### Dataset from [Kaggle](https://www.kaggle.com/datasets/susant4learning/holiday-package-purchase-prediction "Travel Package")
### Context
"Trips&Travel.Com" company wants to enable and establish a viable business model to expand the customer base. One of the ways to expand the customer base is to introduce a new offering of packages. Currently, there are 5 types of packages the company is offering - Basic, Standard, Deluxe, Super Deluxe, King. Looking at the data of the last year, we observed that 18% of the customers purchased the packages. However, the marketing cost was quite high because customers were contacted at random without looking at the available information. The company is now planning to launch a new product i.e. Wellness Tourism Package. Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance or kick-start a healthy lifestyle, and support or increase one's sense of well-being. However, this time company wants to harness the available data of existing and potential customers to make the marketing expenditure more efficient.
## Data Description
| Variable | Description |
| --- | --- |
|CustomerID|Unique customer ID|
|ProdTaken|Product taken or not (0: No, 1: Yes)|
|Age|Age of customer|
|TypeofContact|How customer was contacted (Company Invited or Self Inquiry)|
|CityTier|City tier depends on the development of a city, population, facilities, and living standards. The categories are ordered i.e.|
|Occupation|Occupation of customer|
|Gender|Gender of customer|
|DurationOfPitch|Duration of the pitch by a salesperson to the customer|
|NumberOfPersonVisiting|Total number of persons planning to take the trip with the customer|
|NumberOfFollowups|Total number of follow-ups has been done by the salesperson after the sales pitch|
|ProductPitched|Product pitched by the salesperson|
|PreferredPropertyStar|Preferred hotel property rating by customer|
|MaritalStatus |Marital status of customer|
|NumberOfTrips |Average number of trips in a year by customer|
|Passport |The customer has a passport or not (0: No, 1: Yes)|
|PitchSatisfactionScore |Sales pitch satisfaction score|
|OwnCar |Whether the customers own a car or not (0: No, 1: Yes)|
|NumberOfChildrenVisiting |Total number of children with age less than 5 planning to take the trip with the customer|
|Designation |Designation of the customer in the current organization|
|MonthlyIncome |Gross monthly income of the customer|

## Table of Contents
* [Exploratory Data Analysis](#section-one)
    - [Import Libraries and Dataset](#subsection-one)
    - [Descriptive Statistics](#subsection-two)
    - [EDA Conclusion](#subsection-three)
* [Business Insights](#section-two)
* [Data Preprocessing](#section-three)
    - [Feature Engineering](#subsection-five)
    - [Split Data Train and Data Test](#subsection-six)
* [Machine Learning Modelling](#section-four)
    - [Hyperparameter Tuning](#subsection-eight)
