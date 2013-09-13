# Katie T.'s Maker Lab Log (2013-14)

## September 11

### Maps of London from UVic Library 

* Bacon's Large print map of London and Suburbs (1890 or later) [online](http://www.londonlowlife.amdigital.co.uk.ezproxy.library.uvic.ca/Contents/ImageViewerPage.aspx?imageid=29053&collectF=2&pi=1&prevpos=20129&vpath=contents)
	* other maps in this repository are all pre-20th century
* Bacon's gem map of London and suburbs (c. 1930s) Special Collections G5754 L7A1 1930 B3 
* Print Map: Map Library - map drawers, G5754 L7S1  
* London in maps / Philippa Glanville, G1819 L7G53 1972 oversize

### Maps of Paris from UVic Library

* Nouveau Paris monumental : Itinéraire pratique de l'étranger dans Paris, Special Collections G5834 P3 1900 G3
* Paris map-1957 Maps Drawer G5834 P3 1957

### Maps of New York from UVic Library 

* [Western New York and the Vacinity of New York City Map](http://www.lunacommons.org/luna/servlet/detail/RUMSEY~8~1~33273~1170691)
	* it's not detailed enough 
* [New York City Map](http://www.lunacommons.org/luna/servlet/detail/RUMSEY~8~1~24242~880064) by Servoss, R. D and Isaac H. Blanchard Co. 1902 
* The reaches of New York City, Map Drawers G3792 N4 1939
* [The Heart of New York Grand Central Terminal](http://www.lunacommons.org/luna/servlet/detail/RUMSEY~8~1~24565~900057)

### Huh... 

* "A plan of London on the same scale as that of Paris" Rocque, John, d. 1762. G5754 L7 1766 R6 1970

### Georeferencing: 

* The real question is: what is the best markup practice to use for georeferencing a text?
 	* (An Introduction to Geospatial Markup)[http://dho.ie/sites/default/files/ss2011-SD-Intro.pdf]-- to look at Friday
	* TEI [geo](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ref-geo.html) tag
* took a look at [GIS Manual](http://www.gsd.harvard.edu/gis/manual/georeferencing/)
* Would it make sense for me to sign up for the GIS course in February? 

> "The goal of this course is to provide Geographic Information Systems (GIS) training for graduate students using GIS as a research tool.  Topics covered will include: GIS data types and representation, map projections, importing and exporting spatial data, data integration, attribute and spatial queries.  Students completing this course will have the skills to search for spatial data, add their own spatial data to a GIS, spatially reference data, and perform basic queries including buffers, intersections, and raster calculations. "


### Possible project proposal notes

* oh.... I just realized a) that I have poor reading skills and b) that the project proposal is a collaborative project, which is even better! Scratch previous notes about potential project proposals. 
* Booth's Descriptive Maps of London Poverty (stumbled upon while looking for library's maps of London)
![Listings for Booth's Map](/boothsPovertyMapsList.png)


## September 10

### Workflow

#### an updated and revised workflow draft is located [here](https://github.com/uvicmakerlab/logs/blob/master/2013-14/tanigawa/workflowDraft.md)

* this will be a collaborative document that Alex and Adèle can edit  

#### establish workflow (Draft 2) 

* select texts and editions (1) 
* select appropriate map with consideration to time, detail of map and location (2) (3)
* the map will preferably be one that is appropriate for selected texts
* scan map (stitch images together if necessary or see if the library is able to use their big scanner to scan the map[s])
* upload map to [MudBox](http://www.autodesk.com/products/mudbox/overview)
* markup text with georeferenced coordinates using XML 
* decide where a portion of the text is located (4) (5) (6)
* mark where word count in the location begins and ends
* use XSLT (?) to aggregate word count and location information
* establish ratio for modeling
* take georeferenced word count and divide location-based word count by the total word count of the novel (is there a way to automate this?) (7)
* decide where the center of the mounds will be and how to establish the width of the mound using a rationale that can be applied to multiple novels
* distort the map
* click on the location the text occurs the number of times as established using the ratio (is there a way to automate this?)
* compare maps of both novels! 

(1) Do we need a criteria to establish which editions we use? (If so, what is this criteria?)

(2) Do we need a criteria to establish which maps? (If so, what is this criteria?)

(3) Do we need to choose texts that would share the same map/use similar maps?

(4) What do we do with imagined spaces, remembered spaces and spaces referenced outside of the city we are georeferencing?

(5) How do we represent portions of text where the characters are in transit? 

(6) How do we represent portions of texts that cannot be geolocated with even a loose kind of precision? 

(7) What can we automate?

#### establish workflow (Draft 1) 

* select edition 
* select appropriate map with consideration to time, detail of map and location 
* the map will preferably be one that is appropriate for Secret Agent and Mrs. Dalloway
* scan map (stitch images together if necessary or see if the library is able to use their big scanner to scan the map[s])
* upload map into MudBox
* markup text with georeferenced coordinates using XML 
* the previous instantiation of this project used the cutting edge technology of post-it notes and copy and paste word count techniques, but this does not preserve the data for multiple uses nor does it make it as easy to review as an XML based model would
* mark where word count in the location begins and ends
* decide where the location is
* use XSLT (?) to aggregate word count and location information
* establish ratio for modelling
* take georeferenced word count and divide location-based word count by the total word count of the novel (is there a way to automate this?)
* decide where the center of the mounds will be and how to establish the width of the mount using a rationale that can be applied to multiple novels
* distort the map
* use the ratio from the georeferenced word count
* click on the location the text occurs the number of times as established using the ratio (is there a way to automate this?)
* compare maps of both novels! 

### key questions

* how do we model parts of texts where the characters are walking or otherwise in transit? 
* how do we establish the center of the mound? 
* how do we establish the radius of the mound? 
* how do we choose editions? 
* what is the criteria for the maps? 
* what can be automated? 

### Meeting with Adèle 

* discussed possibility of changing city from London to Paris
* is it possible to map poetry? (New York might be a particularly good case study for this)
* possible novels: Tarr; Quartet; Good Morning, Midnight;  
* How to trace the routes/movement? Do we represent them differently, physically 
* discussed georeferencing small portions of texts as case studies

### Katie's to-do list from meeting: 

* ask Stephen about rationale for London, Secret Agent, Mrs. Dalloway-- could we start with Paris, or is London the best city to begin with? 

### Project Proposal musings (very loose and general, exploratory notes)

* Ideally I would like this to dovetail into something to use for a dissertation. On that note, I was wondering how to integrate my interest in issues around poverty and homelessness, modernist periodical studies, and digital humanities methods. A general question of interest is how do modernist texts construct images of poverty and homelessness? how are these images shaped by contemporary policy? how might these texts and images in turn shape policy around homelessness and poverty? I'm not sure if these are interesting questions to ask to anyone other than myself, nor am I sure right now how to integrate a DH or versioning component. 


## September 9, 2013
* created md file for [MSA talk](/zaxisMSA.md) and revised for possible MLab post (?)
* began work on workflow for Z-Axis
* revised CSDH paper with Jana for submission to CSDH publication 

