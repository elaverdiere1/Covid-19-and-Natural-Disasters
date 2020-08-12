# group_project_5
### Inferential study of the hotspots associated with Covid-19 and Natural Disasters in the United States
***AUTHORS:***<br>
**Matt Paterson, Data Science Fellow, General Assembly, hello@HireMattPaterson.com**<br>
**Eric Laverdiere, Data Science Fellow, General Assembly, laverdiere.eric@gmail.com**<br>
**Matthew Burrell, Data Science Fellow, General Assembly, matthew_burrell@outlook.com**<br>

### How risky is our county?
**Using data related to the deaths from COVID-19 and instances of earthquakes, wildfires, droughts, tornadoes and hurricanes over the last twenty years, and major weather events of the last thirty years, this project creates a user interface that illustrates the relative risks of each.**

### Modeling
**For our Covid data, as well as our earthquake data, we used a KMeans clustering algorithm to group our datapoints geographically. In the case of the Covid data, we ran a second clustering model, again using KMeans, to stratify the datapoints into subsets by how severely each area was affected by COVID deaths.  We then plotted the average deaths per capita (per 100K) by cluster and the actual deaths per capita by county.**<br><br>

**Our final API is a set of maps built in Tableau that show a user all of this data by toggling between them, along with the historical data regarding the aforementioned natural disasters.  If we had more time we would like to create a clustering algorithm that puts all of this data together and predicts by time of year where the government or NGO relief agencies should be directing money and human resources to help our medical infrastructures ahead of the synergistic affects of these mortal dangers.**


This repo contains datasets pulled from various locations, all of which are sited here:

-NOAA- StromEvents Data <br>
-USGS- Earthquake Data<br>
-COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University<br>
-https://github.com/CSSEGISandData/COVID-19<br>
-https://github.com/nytimes/covid-19-data<br>
-Google BigQuery<br>
-https://covid19.healthdata.org/united-states-of-america<br>

