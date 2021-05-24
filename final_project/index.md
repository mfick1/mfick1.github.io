# Final Project 

## Mapping Major Earthquake Activity in Alaska and Potential Effects of Massive Oil Spill from Trans-Alaskan Pipeline on Environment and Wildlife

### Backgroud
The Trans-Alaskan Pipeline was completed in 1977, under scrutiny from Environmental activists in the United States and across the globe. The pipeline snakes its way from the Tundra at the northern border of Alaskan all the way to the southern border where it connects with oil processing stations. Throughout its 40 plus year history, the pipeline has been plagued with problems, in the form of leaks frequent leaks which can cost in the millions and endanger local wilderness and wildlife while poisoning waterways. In 2006, 267,000 US gallons of crude oil spilled nearly unnoticed into Prudhoe Bay in Northern Alaskan killing hundreds of thousands of animals as the oil spread across the coastline over the following weeks. It cost BP, the owner of the Oil in the spill, hundreds of millions of US dollars in resulting fines, loss of profit, and cost to rebuild portions of the pipeline. In 2002, following a 7.9 earthquake near the Delta Junction region of the pipeline, the Denali Fault shifted large portions of the pipeline from their initial positions and caused fears of oil spills in the region due to the displacement. Since these events, fears of massive oil spills along the pipeline as a result of seismic activity have grown and many geologists and scientists who already oppose the use of the pipeline have demanded for heavier regulation and invested preparation to mitigate potential damage from another sudden strong earthquake in the region. 

### Objective
The objective of these maps are to first show the progression and relative locations of earthquake activity in the region of the Trans-Alaskan Pipeline over the past 4 decades since its construction in 1977 beginning in 1980 until 2020. The subsequent two maps assess the potential environmental hazards if the Trans-Alaskan Pipeline were to experience another massive spill as a result of earthquake activity, in the form of poisoning local watersheds which the spread throughout the state. To achieve this, research how the maximum spread of crude oil from the pipeline along any point in case of a strong leak and how far these could spread through the watershed. I then used the buffer function is QGIS to create a buffer of this calculated distance around the pipeline and plotted it over census data of Alaskan Population to assess that upwards of hundreds of thousands in the region could be impacted in some capacity in the event of a major leak. I then used this same buffer to determine how far the oil could spread if not no immediate actions were taken to fully remove it from local rivers and lakes around the spill. The majority of rivers connect across the state, showing that if a spill occurred in just the right location, remnants of oil could matriculate their way through water systems all throughout the state, and even disruption portions of Alaska’s massive Boreal forests in the center of the state. 

### Data 
I used the USGS earthquake catalog to obtain all earthquake point data:
<br>[https://earthquake.usgs.gov/earthquakes/map/?extent=-12.38293,-140.625&extent=68.65655,-49.21875&map=false](https://earthquake.usgs.gov/earthquakes/map/?extent=-12.38293,-140.625&extent=68.65655,-49.21875&map=false)<br/> 
Burrough Level Census Data was obtained using tidycensus and R notebook. Alaskan Lakes, Forests, Airports, and Pipeline were obtained through Packt Publishing as part of the Learn QGIS book written by Cutts and Graser. 


### Maps:
The first map below is a GIF that depicts the progression of seismic activity in Alsaka over the last 4 decades, since the construction of the Trans-Alaskan Pipeline (1980-2020):

<img src="images/Alaskan_Quakes_GIF (1).gif?raw=true"/>

The next map below depicts the potential range of health hazards on Alaskan population in the event of a major burst in the Trans-Alaskan Pipeline:

<img src="images/Impact of Spill on Population (1).png?raw=true"/>

The final map below depicts the potential range of environmental hazards in the event of a mahor burst in the Trans-Alaskan Pipeline: 

<img src="images/Impact of Spill on Environment and Wildlife (1).png?raw=true"/>

