# UFOs

<img src="https://github.com/Donik22/UFOs/blob/main/static/images/nasa.jpg" alt="nasa_img" width="1000" height="200"/>

## Overview

In this Project, a table was built from a JavaScript (JS) array and imported into our dynamic website where the user will be able to interact with the data and filter them based on multiple filters. The table contains 7 attributes per UFO sitting, In this Website, we'll be focusing on 5 main attributes to filter our data. 

The attributes are as follows:
- Date
- City
- State
- Country
- Shape of UFO

The purpose of this analysis is to allow users to filter through these criteria and perform a more in-depth analysis of UFO sightings.

## Results
The initial table should look like this : 
![Search filter and Table](https://github.com/Donik22/UFOs/blob/main/static/images/Filter%20and%20Tables.PNG)
### Errors
The website contains an introductory article and when you scroll down you'll find five filter boxes that accept input and filters accordingly. 
The format given as placeholders must be followed. If the format was not followed or the given data doesn't exist a blank table will be shown with only the headers.

![Error](https://github.com/Donik22/UFOs/blob/main/static/images/blank%20table.PNG)

### Optional
One or all filter boxes can be used. Filling these boxes is optional. note that if one of the criteria does not match the values in the table or the format. a blank table will be returned. Therefore if the user chooses to utilize all filters, they should all match existing data and be in an appropriate format.

## Drawback and Recommendations

### Drowback
1. The data from this website are taken from a JS array, Which means that it will not update automatically. Data recorded after the last update on the JS array won't be displayed.
2. Information about sightings on these websites is limited and no extensive research can be done based on that.
#### Recommendation
1. Data can be appended Manually or it can also be automated using flask and splinter by scraping updated websites.
2. The website can link multiple articles referencing the sightings to give the user more information about the validity of the claim and read people's opinions on it.

