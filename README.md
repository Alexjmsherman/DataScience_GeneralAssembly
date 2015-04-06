# General_Assembly_Data_Science
Final project and homework for General Assembly's Data Science Course


## Project Question

What factors correlate with a seller's listed price for online housing listings?

## Data

I will use craigslist listings as the core data set. Craigslist listing are fairly structured and include the following data:
   
#### Housing Description:
        -Seller's listed price
        -Listing Title
        -Listing Text
#### Housing Attributes:
        {'availability': 'available now',
         'bathroom': ' 1',
         'bedroom': '1 ',
         'cat': 'cats are OK - purrr',
         'data_available': '2015-04-15',
         'dog': 'dogs are OK - wooof',
         'housing_type': 'apartment',
         'laundry': 'w/d in unit',
         'parking': 'attached garage',
         'smoking': 'no smoking',
         'square_footage': '763'}
#### Location Data
        {'address': 123 Random Street,
         'city': 'Arlington',
         'country': 'US',
         'latitude': '11.111111',
         'location_data_accuracy': '10',
         'longitude': '-22.222222',
         'state': 'VA'}
#### Image data
        -number of images
        -size of each image (e.g. 600X450.jpg)
        -image link

## Notes on the Data
Using the above data, I will model the association between the various inputs and the listing price. My metric of success will be to create a model that can predict the listed sales price with 20%, provided the other data points from a listing.

Craiglist does not provide sales data, so the question is determining a metric of user confidence rather than actual housing value - the listed price may not equal the actual sales amount.  

My initial data set will consist of the craigslist housing attributes in the Washington, DC market; however, I may explore the location and image data and/or expand to other housing listing datasets. Some corollary questions of interest include:


* Can i use the latitude and longitude to determine nearby landmarks that may relate to housing value (e.g. metro proximity)?
* Using natural language processing, can I determine important phrases in the listing text and what role sentiment plays in user confidence of housing value
* Using image processing, can I discover important attributes of the gallery image (the image listed as a thumbnail before a user clicks on the listing)
* Expanding the dataset to other markets, how does the importance of attributes differ across the Uniterd States?
* Expanding the dataset to other housing listing websites (e.g. Trulia, apartments.com, padmapper), how do listing prices change across mediumns for similar houses.
    
    
## Why this Topic
I have selected this topic as I am currently searching for a new apartment, and I hope to use this model to optimize my search and get the best value for my money.

Additionally, the topic has potential to utilize many intersting data science topics: 

* web scraping
* geolocation analysis
* NLP / sentiment analysis
* Image processing
    

