# Monroe County Accidents

Originally a LHL boot camp project for honing our skills in API retrieval and data preparation, I always wanted to revisit this to see what more can be done and how to approach it differently.

One main desire and one of the more challenging tasks was setting up Foursquare API venue retrieval using rectangular boundaries. Instead of getting nearest bars for almost 50K accidents, I wanted to create a complete list of bars in the neighborhood. Good idea, since there was only about 100 of them.

Weather data was a bit more tricky. Bulk weather datasets are available but it costs money and the one available for free (World Weather Online) allows for 250 or so API calls per day. Since this is a hobby project, I wasn't gonna spend anything on it other than time. After some searching in various weather data archives, I came upon the [Iowa Environmental Mesonet](https://mesonet.agron.iastate.edu/ASOS), courtesy of Iowa State University. Was able to get hourly readings on all kinds of weather stuff there. Saved the csv and included for your pleasure.

What should be the hypothesis?