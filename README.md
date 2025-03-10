# Geospatial Optimization of Medical UAV Hubs

## Overview
This project aims to determine the optimal location of a theoretical medical UAV hub, like those of Zipline, in Eastern Province, Zambia.  We measure impact based on number of facilities and population served and improvement over road transportation. Operational feasibility is considered based on cellular network coverage, which the drones require for communication with the hub.

## Key Components
* **Geospatial Data**: This includes Zambia's administrative boundaries, health facility locations, road networks, and cellular network coverage pulled from government websites and APIs.
* **Clustering Algorithm**: We use K-Means clustering to group health facilities based purely on geographic location, with adjustments made to limit cluster size based on drone flight limitations.
* **Optimization Model**: We then use PyMCDM to select between clusters based on number of faciltiies served, catchement population, network coverage, and improvements over road transportation.

## Analysis Tools
This project was completed using Python and ArcGIS.
