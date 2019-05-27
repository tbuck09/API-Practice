# API-Practice
This is the repository for the DU Data Analytics Bootcamp Module-6 homework for practice requesting data from an API and using Python for data exploration.

## Objectives
* Request data from the [Open Weather Map API](https://openweathermap.org/api "OMW API")
* Save the data to a Pandas DataFrame
* Save this DataFrame to a csv
    * Saved to the [__Resources__](Resources) folder
    * *Note: Each csv is saved with a unique ID connected to its timestamp*
* Plot the data according to:
    * Latitude vs Max Temperature
    * Latitude vs Humidity
    * Latitude vs Cloudiness
    * Latitude vs Wind Speed
    * Saved to the [__Images__](Images) folder
    * *Note: Each png is saved with a unique ID connected to its timestamp*
* Draw conclusions from the plots
    * Found in the __Observations__ section of this README.md

## Observations
* Wind speeds, on average, are much lower at the equator than at latitudes nearing the poles..
    * Coriolis Force, the rotation of the earth, and Prevailing Winds appear to be the culprits of this observation. In some graphs more than others, it is noticable that latitudes north of 30 experience higher windspeeds on average. This is apparently due to [a buildup of air caused by the earth's rotation](https://www.weather.gov/source/zhu/ZHU_Training_Page/winds/Wx_Terms/Flight_Environment.htm "Prevailing Winds").
* There is a strong trend between distance from the equator and Max Temps.
* There does not appear to be a relation between Cloudiness and distance from the equator, short of some banding at 0% between Latitudes of -40 and -5 as well as 25 and 75.
* Humidity appears to be affected by distance to the equator. In latitudes of -10 to 10, humidity levels lower 50% appear rarely and are concentrated in the northern latitudes. This is likely directly related to the same trend recognized in the Latitude vs Max Temp graph, as humidity is lower when the temperature drops.