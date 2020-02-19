## Cumulative Openings and Retention Analysis for BC Forest Practices Board (2008)

**Project description:** Developed ArcGIS Python scripts for a regional assessment of retention areas versus cumulative openings in mountain pine beetle affected areas in central British Columbia. The study area comprised Prince George, Vanderhoof and Quesnel, Fort St. James and Lakes forest disctricts. We explored two algorithms for generating cumulative openings; the hierarchical buffer/un-buffer methodology put forth in the landscape biodiversity objectives order, and a simple 75 m buffer/un-buffer. We also do sensitivity analysis by looking at cumulative openings generated from cutblocks opened in two date ranges: 1986-2008 (binary_20) and 1976-2006 (binary_30).

The analysis utilized ESRI ArcGIS (version 9.2) functions. The use of Arc presented challenges, mostly in terms of memory, since this was a large dataset, and also due to some fragility in the ESRI codebase (and lack of rich error messaging). The arrival of ArcGIS Service Pack 5 during the last days of coding seems to have helped. Approximately 1500 lines of Python script were written to call Arc functions and manipulate files and data structures. Not including development time, the full batched processing of the 5 districts took approximately 173 hours on a quad processor workstation with 6GB or RAM.

<img src="images/prj_cumm_openings_flow_diagram_s2.jpg?raw=true"/>

### Background:

The legislative requirements under the Forest and Range Practices Act and Forest Practices Code transition require that harvested cutblocks larger than the defined maximums must resemble openings caused by natural disturbance1. To resemble natural disturbance, increased stand structure in the form of; tree retention, understory vegetation and coarse woody debris, is generally required. Tree retention should therefore be higher than defaults for standard size cutblocks. The increased retention will serve a variety of functions including but not limited to:

- increased protection for riparian areas
- maintenance of non-pine species for biodiversity, seed source and future harvest opportunities
- protection of sensitive soils
- increased maintenance of stand structure from either live or dead trees – with intact forest floor
- allowing for cutblock design that more closely mimics natural disturbance.

For the development of within-stand retention practices in salvage blocks following attack by mountain pine beetle (MPB, Dendroctonus ponderosae) stand-level practices are required that help create conditions that resemble, to a reasonable extent, the spatial, temporal, and structural characteristics of natural disturbances. 2 Some key habitat issues that may need to be considered when planning include retaining mature forest attributes such as large live trees and snags, connectivity and isolation effects, riparian reserves and management zones, prompt access management, and maintaining heterogeneity.

This analysis was published in the following [Forest Practices Report](https://www.bcfpb.ca/reports-publications/reports/biodiversity-conservation-during-salvage-logging-in-the-central-interior-of-bc/)
