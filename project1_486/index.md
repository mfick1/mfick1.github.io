# Project 1

## Progression of Seismic Activity in Japan in Relation to Geologic Hazards of Hypothetical Mt. Fuji Eruuption

### Backgroud
These maps are designed to study the progression of major earthquake activity in Japan in the region around Mt. Fuji, the tallest mountain in Japan and one of the most dangerous sleeping active stratovolcanoes in the world. There have been 15 eruptions in recent recorded history since the year 781. Mt. Fuji last erupted in 1707, following an 8.6 magnitude just a few weeks prior that disrupted magma chambers below the island that likely primed the mountain for eruption. Since then, Mt. Fuji has uncharacteristically laid dormant for over 300 years. Many scientists were certain an eruption was imminent following the uptick in seismic activity in the region over the past 5 decades, culminating in the 2011 9.1 magnitude Tohoku earthquake just shy of 400 km from the base of Mt. Fuji. This massive earthquake was the 4th strongest earthquake in all of recorded history, and geologists have noticed that this quake disrupted magma chambers once again below Mt. Fuji, leading to speculation of imminent eruption any time within the next couple decades. 

### Objective
The objective of these maps is to first show the progression and relative location of earthquake activity in the region of Mt. Fuji around Japan’s central island of Honshu over the past 5 decades beginning in 1970 until 2020. The subsequent two maps assess the potential hazards if Mt. Fuji were to erupt soon, in the form of Lava Flow, Pyroclastic Flow, and Raining Ash that would blanket a large portion of the island. To achieve this, I first researched historic records of volcanic hazards from previous eruptions at Mt. Fuji and their relative distances as well as the leading predictions of potential modern hazards from the speculation of top volcanologists. I then used the buffer function is QGIS to create 3 separate buffers for each resulting hazard, and the best estimations of their relative range of dispersal. This results in two maps depicting the range of hazards and how much of the Japanese population would be at risk from each. Japan’s largest city of Tokyo would become completely paralyzed just hours following an eruption, as ash would complete blanket the majority of the city and surrounding suburbs and potentially cut off vital evacuation routes as millions of citizens attempt to flee the fallout. I used the summation function in QGIS to estimate the total population in danger from an eruption and found this total to be approximately 26 million, which is not far off from the speculated 25 million most volcanologist estimate. 

### Data 
I used the USGS earthquake catalog to obtain all earthquake point data:
[found here](https://earthquake.usgs.gov/earthquakes/map/?extent=-12.38293,-140.625&extent=68.65655,-49.21875&map=false) 
<br>Japanese census data was used for population estimates from the Statistics Bureau of Japan:[found here](https://www.stat.go.jp/english/data/chiri/map/index.html)<br/> 


### Maps:
The first map below is a GIF that depicts the progression of seismic activity in Japan over the last 5 decades (1970-2020):

<img src="images/Japan Major Earthquakes over 50 years (1970-2020) (1).gif?raw=true"/>

The next map below depicts the potential range of geologic hazards of hypothetcial Mt. Fuji Eruption:

<img src="images/Potential Hazard Zones from Mt Fuji Eruption (1).png?raw=true"/>

The final map below depicts the potential range of Japanese population at risk from geologic hazards of potential Mt. Fuji eruption. 

<img src="images/Population in Danger from Eruption (1).png?raw=true"/>
