# City Health
This project is an application that displays statistics about COVID-19 and air quality about a desired place. The motivation behind this application is to help people to stay safe in the current environment at home and elsewhere, environmentally and pandemic wise. 
 
## The technologies we use in this application
### J-Query and JavaScript
We use J-Query and JavaScript to make the application interactive.
 
### Tailwind
Tailwind is the CSS framework in this application because it is very customizable and also makes it easy to build a responsive interface within the html file without the need for custom CSS.
 
### Moment.js Library
Moment.js’ library allows our application to access the GOV.Uk Coronavirus Api's data for specific dates. We use different moment formats to be able to access varying COVID-19 information.
 
### APIs
The API's we use within this application are: OpenWeather Geocoding API, OpenWeather Air Pollution API, Find That Postcode API and the GOV.Uk Coronavirus in the UK Open Data API.
 
* OpenWeather Geocoding API allows the computer to access geographical coordinates when the user searches for a place.
* OpenWeather Air Pollution API then can use the coordinates of the searched place and provide the current concentration of pollutants in the air of that location that can display on the interface.
* Find that Postcode API is of necessary use to acquire the GOV.Uk COVID-19 API and access its statistics because of how the statistics are grouped.
* Lastly we use GOV.Uk Coronavirus in the UK Open Data API in this application to be able to access and display the current COVID-19 statistics in the Uk.
 
## Challenges that occurred in production
* A challenge we experienced throughout the project was the use of remote branches as oftentimes conflicts would occur when we tried to merge them to the main branch.
* A challenge we faced in this project was accessing the data about the COVID-19 R-rate \(transmission rate\) as it didn’t seem to display. We figured out that this was because the R-rate is measured every Friday. The solution we found was by setting the date for the moment to the previous Friday, so we had to set a moment to the date of the previous Friday. 
* Another issue we had, with the other COVID-19 statistics, was that they would not display in the morning. The way we resolved this was to set the related moment’s date to the previous day.  
* Another challenge was figuring out how to access,through Find that Postcode API, more remote location's associated regional geographical code. This was solved by associating it with a larger region in the  Find that Postcode API. This is important in regards to this application as that is how the computer retrieves COVID-19 data.
* A further obstacle was not being able to find an easily accessible API for global COVID-19 current statistics, this meant we had to use a filter in the OpenWeather Geocoding API to so that it only accesses locations in Great Britain.
 
## What are some future things we want to implement
* To find a way using JavaScript to remove duplicates in the local storage.
* To find an API that makes it possible to easily access COVID-19 data from All over the world, and if that is not possible just a larger section of the world.
* To create a forecast for the air pollution levels within a place.
* To make the website more visually stimulation by adding interactive graphs for both air pollution and COVID-19 statistics. 
* To add an interactive map using Google Maps API to display area’s levels of COVID-19 and air pollution.
* Lastly since our website’s main message is about informing people about factors that could affect their health, we would add relevant links to educate people on how to stay safe in this environment: such as the uk government site about staying safe and prevent spreading of covid and for air quality a link from british lung foundation about how to protect yourself against air pollution.

## Deployed Application

### On screen width of 1024px and above
![Deployed Application On minimum screen width of](./assets/deployed-application-computer.png?raw=true)
### On minimum screen width of 768px and below 1024px
![Deployed Application On minimum screen width of](./assets/deployed-application-tablet.png?raw=true)
### On screen width of below 768px
![Deployed Application On minimum screen width of](./assets/deployed-application-phone.png?raw=true)

[Link to Deployed Application](https://dyl4n1997.github.io/City-Health/)


