# King County Home Sales and Features

## Overview and Business Understanding

My project aims to discover the top features of a home to increase the home's value. __[Here](https://docs.google.com/presentation/d/1FV6ToG1TDWpQn5oegywazw8A7p6ldPxW2a7nZ2b5VAs/edit?usp=sharing)__ is the link to my presentation.
Questions: What features of a home increase its value?  Which features increase a home’s value the most?  By what amount could these features increase a home’s value? 


## Data Source and Data Description

This data comes from the King County House Sales dataset.

The primary columns I used from these databases to determine home sale features were:

price bedrooms bathrooms sqft_living sqft_lot floors waterfront condition grade yr_built

Taking these variables into consideration, I investigated the home features that correlated to the highest value to a home. 

I created the following visualizations from this data:

![Heat Map of Correlating Features](https://user-images.githubusercontent.com/98120389/204942276-922886bd-ad47-4a93-9f44-9f48cab94e99.png)

![Most Correlated Feature and Sale Price](https://user-images.githubusercontent.com/98120389/204942423-8333c502-89dc-490b-91d0-07fc8598ee08.png)

![Second Most Correlated Feature and Sale Price](https://user-images.githubusercontent.com/98120389/204942461-6a6532ee-b765-4c91-af13-1ebd7861d9b6.png)

![Third Most Correlated Feature and Sale Price](https://user-images.githubusercontent.com/98120389/204942510-94596214-a02c-49d6-b3c8-468dedb05e98.png)

I ran 256 different models and determined that the combination of features with the highest training and validation scores included all features (all columns listed above).

My model was able to explain around 64% of the variance of the price of a home.

![Final Model](https://user-images.githubusercontent.com/98120389/205406935-c8ace9ba-92c2-4262-a53d-9dfefacc72a8.PNG)


# Conclusion and Recommendations:

After calculating the coeffiencients, I came to the conclusion that the three home features below will provide the largest value to a home:

Square Feet: Each square foot of living space could increase your home’s value by $182

Grade: Increasing the grade of your home (the construction quality and design) could increase your home’s value by $127,477

Bathrooms: Each additional bathroom could increase your home’s value by $50,786. 




Navigating the repository:

Data can be found in zippedData folder

student.ipynb contains the coding and markup

presentation.pdf is Google Slides presentation of information


