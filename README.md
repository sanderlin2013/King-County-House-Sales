# King County House Sales Analysis 

## Overview
Here we will be looking into the King County House Sales dataset to find information on how home renovations might increase the estimated value of homes (and by what amount) for the magazine 'Home Owners Yearly', who wants to put out an article on what renovations will or will not be likely to improve the value of middle class and upper middle class homes.


## Business Problem
The magazine gave us a few questions to focus in on.
### Questions
- Will increasing the living area size lead to an associated increase in the value of the home?
- Will adding bedrooms or bathrooms lead to an associated increase in the value of the home?
- Is the grade or condition rating of the house associated with the value of the home?

## Data 

In order to do this, we will be looking at a data set on houses and housing prices from [King County in Washington State](https://en.wikipedia.org/wiki/King_County,_Washington).

### Dataset Size
After some initial data cleaning, we were left with 21,225 houses, whose mean sale price  was $535,000.

### Limitations of Dataset

There are some limitations inherent to this dataset. First and foremost, this dataset is all from King County, WA. This is a fairly affluent and densely populated area [(Wikipedia page)](https://en.wikipedia.org/wiki/King_County,_Washington), and as such the recommendations and conclusions from this data may not hold true for other areas with different characteristics (e.g. rural areas). More information and analysis is necessary to determine what neighborhoods and counties can use these recommendations. 

Additionally, there are many types of renovations that aren't included in the dataset (e.g. renovating the plumbing, new roof, adding a deck, ect.), which limits the specificity of the recommendations. 

### Why We Used This Dataset
Despite the above limitations, this dataset does represent a middle and upper class neighborhood, which is the demographic that the magazine is trying to appeal to. It does contain the information on bedrooms and bathrooms (which were some of the magazines specific questions that they wanted answers to) and was easily available. 

##Method

