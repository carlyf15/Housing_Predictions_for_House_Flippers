# Module 2 Project: Housing Predictions #
________________________________________________________________________________________________________________

## Overview ##
________________________________________________________________________________________________________________
Buying a home can be a great experience but can also be a processed riddled with complication and unanswered questions, especially in a city as popular as Seattle. Buying a home in a major city can feel like an extremely expensive Ebay auction - you have no idea how many people are bidding on the same home as you and homes often go over asking price within 24 hours of listing. The intention of this project was to use a dataset containing housing information from King County (Seattle, Washington) to predict prices of the housing market. As a buyer, this is invaluable to you because we can help you predict home costs to inform your budget and playing the offer game. Also, our model can help predict the value added to your home when considering renovations. Adding a bathroom? Improving the backyard? Our model can help you perform a cost-benefit analysis and give you a powerful bargaining chip with contractors.


## King County ## 
________________________________________________________________________________________________________________
According to the U.S. Census bureau King County's population is a staggering 2.253 million residents. 20% of it's residents are under 18, and only 13.2% are over 65. It's a relatively young city. It is roughly 50/50 male vs. female. King County residents are 65% white and 20% Asian. It has 57% owner-occupied housing and the median value of these homes is $493,500 (more than double the national average). 93% of residents have a high school diploma and another 51% have a bachelor's degree, and the median income is $89,418. This is just a brief snapshot of the people who inhabit King County but does reveal that King County is full of young to middle-aged, middle class families who are mostly white. While living in King County is slightly cheaper than other counties within Seattle, it's still pricey. This isn't unusual in today's world though - with a significant increase in young people choosing the city over the suburbs cost of living in major cities is steadily increasing. 

## Contents ##
________________________________________________________________________________________________________________
In this Repo you will find the following:

- 4 ipynbs
	1. Preprocessing
	2. Exploratory Data Analysis 
	3. Modeling + Validation 
- Non-Technical Presentation 


## Methodology ##
________________________________________________________________________________________________________________
* Tools
	-pandas, numpy, sklearn, matplotlib, seaborn, statsmodel
*Data Cleaning 
*Exploratory Data Analysis 
*Modeling


## Limitations ##
__________________________________________________________________________
Building a linear regression often requires limiting the scope of the prediction. The real estate market in King County is quite variable and in order to make our model applicable it was necessary to focus on a specific market. The following specifications define the market out model can be used for.
	* Listings which have:
		- <4,000 sqft
		- <6 Bedrooms
		- <6 Bathrooms
		- <15,000 sqft lot size


