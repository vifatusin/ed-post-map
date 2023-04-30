# EPA Data Analysis and Mapping for Ed Post

Studies from the [Government Accountability Office (GAO)](https://www.gao.gov/assets/gao-22-104606.pdf) and the University of Utah have shown that school districts that have received a grant from the government for a natural disaster are in counties or areas where high air pollution and high noise pollution exists. I was assigned to create two similar maps - one showing the school districts that received a grant and another showing the rates of air pollution affecting the neurological system per county. 

## Methodology

For the first map/illustration, I reached out to the GAO to ask for the data used in their analysis. I received a csv of all the districts that received grants and the ones that didn't. This only required me to create a geojson file for mapping.

For the second, I used [2018 air pollution data affecting neurological health from the Environmental Protection Agency](https://www.epa.gov/AirToxScreen/2018-airtoxscreen-assessment-results), which contains neurological air pollution rates for each county. Similar to the study from the University of Utah, I calculated the percentile of the data, specifically the 75th and 90th percentiles, to see which counties had the highest air pollution rates. Counties that were in the 90th percentile included counties with major metropolitan cities such as Los Angeles, Chicago, New York City, and so on. 

[The map can be seen here in this story published in Ed Post.](https://www.edpost.com/stories/what-is-environmental-activism-youth-of-color-creating-justice)

**_NOTE: The map/illustration showing the school districts that received a grant from the government for a natural disaster was not used in the final pieces._**
