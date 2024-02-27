In WeatherPy challenge:
  In this module I created Plots to showcase the relationship between weather variables and latitude.
I used citipy to gather a list of cities with their random latitude and longitude and then printed a count for the cities in the library.
The first requirement was to use Open Weather Map API base URL to reference several sets of data for each city:
  latitude, longitude,  map temperature, humidity, cloudiness, wind speed, the country and the date of the temperature.
  I ran a data list to process the name of each city in a respective list. 
I then referenced the cvs file for cities to create a dataframe.
I built a scatter plot for the following variations:
  latitude vs. temperature
      In this plot graph one result I noticed was that the higher the latitude got the higher the temperature. 
      I also noticed there was a generalization on the temperature; the greater the latitude, whether negative or positive, the greather the temperature. 
  latitude vs. humidity
      This plot graph showed a lot scattered data plots, but it seems to me that the higher the latitude, the higher the humidity.
  latitude vs. cloudiness
      This scatter plot didn't have a relative pattern to me. The cloudiness did not depend on the latitude of the city.
  latitude vs. wind speed
      The wind speed didn't seem to have a relative pattern either. It seems that wind speed also does not depend on the latitude either.

  The second major requirement was to compute a linear regression for each of the relationships we looked at previously.
   I first built two data frames: one for the southern hemisphere and one for the northern hemisphere.
   I then created a linear regression plot for temperature vs. latitude of both the northern and southern hemisphere and looked at their respective R values.
     From these two plot maps I concluded: 
         The high r value in the northern hemisphere indicates a strong positive relationship between latitude and max temperature.
         R values = 0.3 in the southern hemisphere which is weak positive correlation.

  I then created a linear regression plot for humidity vs. latitude of both the northern and southern hemisphere and looked at their respective R values.
     From these two plot maps I concluded: 
         The r values indicate there is a very weak to no positive correlation in the northern hemisphere between humidity and latitude.
         In the southern hemisphere there is almost no positive correlation between the humidity and latitude.

         
  I then created a linear regression plot for cloudiness vs. latitude of both the northern and southern hemisphere and looked at their respective R values.
     From these two plot maps I concluded: 
         For both northern and southern hemisphere this is a weak to no positive correlation between cloudiness and latitude.

  I then created a linear regression plot for wind speed vs. latitude of both the northern and southern hemisphere and looked at their respective R values.
     From these two plot maps I concluded: 
         For both the northern and southern hemispheres there is a weak to almost none relative correlation between the latitude and wind speed.

Vacation Py Python Challenge-
    In this I struggled to get the correct projection support downloaded. No matter which way I tried; whether with conda or pip install, I could NOT get them to download.
    I went ahead and build the data sets needed to complete this module challenge even though it would not run for me.
      I built a Dataframe from the cities csv file. I then tried to create a plot map of the humidity and it's respective city name.
      I then built a dataframe to find my ideal weather condition:
          A temperature between 69.8 and 80.6 degrees,
          A wind speed of < 4.5
          and a cloudiness of zero.

I took the ideal city dataframe and created a data frame for hotels in that area.
For the final step I took a geoapify key and 
