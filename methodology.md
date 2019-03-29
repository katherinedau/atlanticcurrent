---
layout: page
title: Methodology and Technical Notes
---
Although tied to another work, this project should be usable for a wide audience. I built this map by cloning Dawn Childress’ [flaneur]( https://github.com/kirschbombe/flaneur), a Jekyll theme. I have made my map publicly available in a GitHub repository, [atlanticcurrent]( https://github.com/katherinedau/atlanticcurrent). My complete data set, which includes location, coordinates, and name of church. I welcome anyone else to use parts or all of this repository and data as I have done with flaneur (with proper acknowledgement, of course).

#### Methodology

As Anne Knowles points out in her article, [The contested nature of historical GIS](https://eds.b.ebscohost.com/ehost/detail/detail?vid=0&sid=fb921822-d8f8-4c6b-aba1-5a2b069007e7%40pdc-v-sessmgr03&bdata=JnNpdGU9ZWhvc3QtbGl2ZQ%3d%3d#AN=91840444&db=a9h), historical GIS has struggled to establish “the why” in their mapping projects. With this in mind, I have tried to clarify throughout my project *why* my web map matters. My project falls under Faye Taylor’s third category of GIS in multidisciplinary medieval history, as described in her chapter, “Mapping Miracles: Early Medieval Hagiography and the Potential of GIS” in Alexander von Lünen and Charles Travis’ volume [History and GIS]( https://link.springer.com/book/10.1007%2F978-94-007-5009-8) (112). Taylor calls this area of historical GIS mapping more “nebulous” but also more accessible and flexible than traditional print resources. I have developed my map in hopes that it will be flexible and accessible for a wide array of audiences. Although dealing with material several centuries older, Taylor’s work is particularly relevant to mine in its reliance on miracle stories and myths in its construction of geographical narrative.

#### How locations were identified

After combing through José A. Martínez Puche and Rafael del Olmo Veros’ *María, Madre de la Hispanidad,* I created a spreadsheet with the name of the town, province, and autonomous region of each location in Spain that claims Guadalupe or Remedios as patron. From this point, I used google maps to attempt to locate a church, chapel, or shrine that might house the image. This task proved easier in some cases than in others. While some towns named a church after their patron, others seems to have no churches at all. Wikipedia and town council websites became invaluable when dealing with sites like these. This builds on the work of Puche and Veros by adding much more information. In their collection, they sought to catalogue Marian devotion as a whole in the Old and New Worlds. I have taken their work as a starting point, and have located coordinates of churches and chapels where these images reside. Where possible, I have sought to include images of the church and icon, origin myths, and other surrounding information.

#### Plotting locations

With coordinates, a location name (listed in my YAML header as “desc”), and the name of the town I began to generate pins. Flanuer is structured to create points in the format of blog posts. This means that the creation date plays an important role in the pin generation. Because most of these cults cannot be nailed down to a specific date, this piece of information was irrelevant and confusing to include in my site. I removed the date from the pages and the article index in the css. For each location, I included the name of the town, its province, and its autonomous region, and its

#### The Map

The map that *The Atlantic Current* uses [Leaflet]( https://leafletjs.com/), which is built with JavaScript. You do not need to know JS to use this tool. The map tiles themselves come from [mapbox]( https://www.mapbox.com/maps/).

#### Images

All images are sourced from Wikimedia commons or have been taken by the author. This is indicated in the caption of each image.
