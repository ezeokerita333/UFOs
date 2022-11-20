# Overview of Project
The purpose of the project was to provide a more in-depth analysis of UFO sightings to enable users to filter for the for multiple criterias including the date, city, state, country, and shape in the data at the same time. 

# Results
The entire reason for this project was specifically to use the date, city, state, county and shape to fliter data for the users. So, basically when you input a date of choice and click enter the data runs the filter code right away, can also be furthermore narrowed down by including the city, state, county and shape to find your specific choice of data. 
As seen in image below, the data is filtered using; 

```
datetime: "1/1/2010",
city: "willow",
state: "ak",
country: "us",
shape: "formation"
```
                                                 
![image1](/static/images/image1.png)
                                                 
This bought out just one result showing all filters searched for, including the duration of "7mins" and a comment of "four orange red objects suddenly appear 12:01 am new years move north then south and dissapear".
Also in image, the data is further filtered with less criterias;

```
datetime: "1/1/2010",
state: "ca"
```

![image2](/static/images/image2.png)

This bought out 16 results including the city, country, shape, duration and comments of the common filters searched for which was datetime and state.

# Summary
One drawback of this new design was that it was case sensitive, thus, if a user makes mistake of inputing capital letters in any word to filter the data, no result will be shown. Therefore, my first recommendation to give for further development would be;
- To make provisions, if possible, for the filtered words to not be case sensitive.
- Lastly, to also make provisions, if possible, for the filtered words to have partial values in the case where the user cannot type in the full details to be searched for.
