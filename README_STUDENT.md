# Module 2 Project: Housing Predictions for House Flippers #
________________________________________________________________________________________________________________

## Overview ##
________________________________________________________________________________________________________________
Flipping houses for a living isn't new but in an ever shifitng housing market can be wrought with disapointment. The goal of this project is to create a model that will provide flippers looking to turn houses in King County with information to help make educated business choices. Where do you buy? What features would be most cost effective to add? When do I buy and when do I sell? We use a regression analysis of real estate information from 2014/2015 in this county to help give powerful answers to these questions to give both newcomers and pros the confidence to flip without flopping. 

## King County ## 
________________________________________________________________________________________________________________
According to the U.S. Census bureau King County's population is a staggering 2.253 million residents. 20% of it's residents are under 18, and only 13.2% are over 65. It's a relatively young city. It is roughly 50/50 male vs. female. King County residents are 65% white and 20% Asian. It has 57% owner-occupied housing and the median value of these homes is $493,500 (more than double the national average). 93% of residents have a high school diploma and another 51% have a bachelor's degree, and the median income is $89,418. This is just a brief snapshot of the people who inhabit King County but does reveal that King County is full of young to middle-aged, middle class families who are mostly white. While living in King County is slightly cheaper than other counties within Seattle, it's still pricey. This isn't unusual in today's world though - with a significant increase in young people choosing the city over the suburbs cost of living in major cities is steadily increasing. 

## Contents ##
________________________________________________________________________________________________________________
In this Repo you will find the following:

- 4 ipynbs
	1. [Preprocessing](http://localhost:8888/notebooks/Preprocessing.ipynb)
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


