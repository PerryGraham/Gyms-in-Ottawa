# - Work In Progress -

### Where is the best place to open a gym in Ottawa, and what type is most prefered ?

##### Here is what the data shows:

Geo-spatial analysis of gym locations across Ottawa, Canada 

  By: Graham Pinsent
  
Tools used: GeoPandas, Pandas, Folium, and Contextily.

![](https://i.imgur.com/ztgs6hg.png)

This is a screenshot of an interative map found in the notebook.
The colours of this map represent the population estimate for each neighbourhood and the circles are gym locations, where the size of the circle represents the size of the gym. 


## Data Collection 
* Used google maps and excel to create a list of all weight lifting gyms across Ottawa.
* Population data downloaded from [Open Ottawa](https://open.ottawa.ca/datasets/ottawa-neighbourhood-study-ons-neighbourhood-boundaries-gen-2?geometry=-78.412%2C44.912%2C-73.186%2C45.589&selectedAttribute=POPEST)
* In order to be included the gym had to have 5+ ratings or pictures of the inside of the gym, showing weights. This was so that small private studios and personal trainers listed as gyms would be excluded from the data set. 
* The size column of the data is based off pictures; 3 - large, 2- medium, 1 - small, 0 - Unknown. Unknown means that there were no pictures to determine an estimated size. Unknown gyms are likely towards the smaller size, because most medium-large gyms would have many pictures.
