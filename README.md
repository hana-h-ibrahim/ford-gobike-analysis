# Ford GoBike Analysis Project

 I will do data analysis on the Ford GoBike dataset. To explore the dataset's variables and comprehend the data's connections, I will utilize data visualization packages. This section's investigation progresses from simple univariate relationships to multivariate relationships. Ford has  made this data available to us [at this provided URL](https://www.fordgobike.com/system-data).

## Summary

Here are a few questions in which I would have hoped to see more information:

 - Duration of Bike Trips in General
 - Distribution of Age in Members in General
 - Distribution of Gender in Members in General
 - Distribution of User Type in Members in General
 - How the 2 Categories Genders and Member Types Influence Duration and Age

## Key Insights

 - To begin with, I was simply interested as to how many rides were taken in total. The graphic below shows that the peak of rides lasts around 550 seconds. 
 - Peak of member birth year is roughly around 1985 which means that the peak of age of members is around 35 years old.  
 - The graph shows that 75% of members (most members) are males then 23% of members are female. The graph shows that the other members are less than 2%.
 - The graph shows that subscribers are around 150000 while customers are less than 25000 of members.
 - For different user types both are appearing comparative patterns for age and trip duration, however, there is a minor higher age bias for subscribers with longer trip durations. The quantity of longer-duration trips is greater for males, but the proportion is higher for women and others; moreover, others have one more peak at roughly the age of 55 for longer-duration trips. 

## Dataset

There are 183,412 bike trips in the dataset with 16 features. However, the dataset contains some missing information. There are only 174,952 bike trips with complete information. 
Here are the features provided to us.

```
 - Trip Duration (in seconds)
 - Start Time and Date
 - End Time and Date
 - Start Station ID
 - Start Station Name
 - Start Station Latitude
 - Start Station Longitude
 - End Station ID
 - End Station Name
 - End Station Latitude
 - End Station Longitude
 - Bike ID
 - User Type (Subscriber or Customer - "Subscriber" = Member or "Customer" = Casual)
 - Member Year of Birth
 - Member Gender
```

## Files Included

Here's a brief description of all the files at are available as part of this project.

 - **ford-gobike-trip-data**: This folder contains all the data we downloaded and then later assembled / cleaned for use in this project
 - **ford-gobike-exploration.ipynb**: This jupyter notebook is where we do all the exploration of the data to be used in our explanatory analysis and slides later.
 - **ford-gobike-explanation.ipynb**: This jupyter notebook synthesizes the information gleaned from the exploration notebook and will be the foundation for the slide deck down below.
  - **output_toggle.tpl**: Provided by Udacity and the good folks who built nbconvert, this hides the code in my slide deck built off the jupyter notebook above.
 - **ford-gobike-explanation.slides.html**: And finally, this is the slide deck that is built off the jupyter notebook above.

## Packages

These are the following packages I used.

```
# import all packages and set plots to be embedded inline
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sb

%matplotlib inline

# suppress warnings from final output
import warnings
warnings.simplefilter("ignore")```
