# <center> Ben McKay - Portfolio of GIS Work </center>
<center> I am a undergraduate of University of Auckland, with a double major in Marine Science and Geographic Information Science (GIS). Appended below are various examples of GIS work and other programming work I've done during the course of my study.

  
  ### <center> Folium Map displaying various Airbnb statistics in San Francisco </center>

  
Following the sourcing of airbnb data from <a href ="http://insideairbnb.com/san-francisco">InsideAirbnb</a>, I was able to perform a query using PostgreSQL to create a Folium map with the Folium package, with the following code being used to produce the map:
 <img width="1705" alt="Folium Code" src="https://user-images.githubusercontent.com/109936302/182288746-8383abb5-250c-49ca-a835-86b5567a6c28.png" align="middle">

### <center> Matplotlib Map displaying tree census data (red) in New York City for 1995 (left) and 2015 (right) </center>
  <html>
    <img src=
"https://user-images.githubusercontent.com/109936302/182289659-8a5b1bb6-2a4c-414f-a71e-7719a16c627d.png"
        alt="1995 Tree Distribution"
        align="left"
        width="475"
        height="400">
    <img src=
"https://user-images.githubusercontent.com/109936302/182289662-28f2ee5d-b057-4f55-8a47-751b32be9645.png"
        alt="2015 Tree Distribution"
        align="right"
        width="475"
        height="400"> 
</html>

<br><br><br>The Matplotlib package was also utilised within PostgreSQL <b> Or python double check with Dad </b> to produce maps, as seen above with two maps showing the change in tree distribution in New York City between 1995 and 2015 using tree census data sourced from <a href ="https://www.kaggle.com/datasets/nycparks/tree-census">Kaggle</a>.
  
### <center> Thematic Maps (ArcGIS Pro)
I created numerous thematic maps on ArcGIS Pro, including a thematic map that displays the above ground carbon distribution (AGC) for shrubland and forestry in Auckland (left) enabling the ability to identify any patterns. <br><br>Thematic maps were also used to display the various deforested areas in Heilongjiang Province of Northeast China in 2000 (right), finding a pattern of deforested areas concentrating near river and stream channels.

<img width="400" alt="Thematic Map AGC distribution" src="https://user-images.githubusercontent.com/109936302/182570388-c5851869-9029-4331-b0dc-d82cb1f2fc6f.png" align="left">
<img width="500" alt="Thematic Map 2" src="https://user-images.githubusercontent.com/109936302/182570660-a8cf64ee-6fd9-4b91-89b4-348467bf37e2.png">



### <center> Network Analysis (ArcMap)
I performed a network analysis on Mt Eden Train Station in Auckland, NZ to calculate the catchment area to identify how many people would walk to the train station.
<p align="center">
 <img width="516" alt="Mt_Eden_Catchment" src="https://user-images.githubusercontent.com/109936302/182570155-816119c2-3969-4bc6-b675-edf36806b424.png">
</p>

### <center> Shoreline Change Analysis (ArcMap) 
I performed an analysis on shoreline change at Whangamata Beach (left) and further north of Whangamata (right) to identify the pattern of movement by georeferencing historical aerial photographs. 

<img width="400" alt="Whanga Beach" src="https://user-images.githubusercontent.com/109936302/182306331-f54efcb3-b373-4bbf-b7a7-90b1b2f97af7.png" align="left"  height="400">
<img width="400" alt="North Whanga" src="https://user-images.githubusercontent.com/109936302/182306419-5ab24284-3f23-4d4d-827d-25ca7efd8079.png" align="right"  height="400">


<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>One of the tools used was DSAS (Digital Shoreline Analysis System) which displayed the Net Shoreline Movement (m) results in 10m transects over the approximate 80 year period of aerial photographs (1944 - 2020). Allowing me to identify the rate of either accretion (blue) or erosion (red) that had occurred at Whangamata.
<p align="center">
  <img width="400" alt="DSAS image" src="https://user-images.githubusercontent.com/109936302/182306229-536dcaa2-c438-4230-8c60-684c7a929968.png" />
</p>

### <center> Google Earth Engine
Google Earth Engine was utilised to perform a supervised classification - in which the algorithm was trained by myself - on Toshka Lakes across 3 different land cover types: Land (yellow), Agriculture (green), and Water (blue). 
<p align="center">
 <img width="912" alt="Land_Cover_Toshka" src="https://user-images.githubusercontent.com/109936302/182569478-73df57d7-6b59-42b8-b65d-26326b2be0f7.png">
</p>
<br><br>Google Earth Engine was - through supervised classifications - used to produce maps that displayed changes in the aforementioned land cover types across several years.
<p align="center">
  <img width="1065" alt="Toshka_Difference" src="https://user-images.githubusercontent.com/109936302/182569938-21edf10f-7592-4da3-b7cd-44b85110cabe.png">
</p>


#### NDVI Analysis through Google Earth Engine
I also used Google Earth Engine to perform NDVI analyses', as seen with the NDVI Analysis of Santa Barbara, Iloilo, Phillipines (below) where blue and red represent minimal NDVI values and yellow and green represent high NDVI values.
<p align="center">
  <img width="470" alt="NDVI Analysis" src="https://user-images.githubusercontent.com/109936302/182568665-df7fa60c-11c3-4622-b97f-9b6e391f957b.png">
</p>  

### <center> R
<p align="center">
    <img width="600" alt="Detailed Forest" src="https://user-images.githubusercontent.com/109936302/182295879-54d4080e-5216-4059-bf42-9d96c03daefc.png" />
  </p>
R was used within Marine Science to create plots such as the forest plot seen above. This forest plot was used for a meta-analysis report to identify any patterns between similar studies for consistent response variables.
