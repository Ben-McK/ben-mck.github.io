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
  
### <center> Multi-Criteria Evaluation (ArcMap)
I performed a Multi-Criteria Evaluation on the 
  
### <center> Network Analysis (ArcMap)
I performed a network analysis on Mt Eden Train Station in Auckland, NZ to calculate the catchment area to identify how many people would walk to the train station.

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
  <b>INSERT IMAGE OF 4 IMAGES</b>
<br><br>Google Earth Engine was - through supervised classifications - used to produce maps that displayed changes in the aforementioned land cover types across several years.
  <b>INSERT IMAGES OF HOW LAND COVER CHANGE OVER TIME</b>

  
### <center> R
<p align="center">
    <img width="600" alt="Detailed Forest" src="https://user-images.githubusercontent.com/109936302/182295879-54d4080e-5216-4059-bf42-9d96c03daefc.png" />
  </p>
R was used within Marine Science to create plots such as the forest plot seen above. This forest plot was used for a meta-analysis report to identify any patterns between similar studies for consistent response variables.
