# Some crazy polygons

A few examples of 'crazy polygons' as found in GIS.
Crazy here means that they contain several vertices and/or several inner rings (also called holes, or inner boundaries).


The ones here are all publicly available, and are usually polygons reprensenting land cover.
They have been obtained by converting a grid to a vector format.
I usually use them to test the capabilities of code I write to process GIS datasets.

The EPSG of all the polygons is 4326 so that they can be visualised direclty here in GitHub (just click on a one geojson to view it).

I'd be grateful if you submitted other ones through pull requests.


## Details

| dataset   | total # vertices | # inner rings | source | OGC valid |
| --------- | ----------------:| -------------:| ------ |:---------:|
| 021L      |          148,612 |         5,132 | [Canada Land Cover](http://www.geobase.ca/geobase/en/data/landcover/index.html)    | false     |
| 085M      |          192,355 |         7,684 | [Canada Land Cover](http://www.geobase.ca/geobase/en/data/landcover/index.html)    | false     |
| canada    |          193,279 |             0 | [Large Scale International Boundary Lines ](https://hiu.state.gov/data/)           | false     |
| cleveland |        1,689,703 |        66,908 | [Cleveland Metroparks](http://clevelandmetroparks.com)                             | false     |
| EU-199948 |        1,189,903 |         7,672 | [Corine land cover](http://www.eea.europa.eu/data-and-maps/data/clc-2006-vector-data-version-2)    | false     |
| EU-180927 |          102,272 |           299 | [Corine land cover](http://www.eea.europa.eu/data-and-maps/data/clc-2006-vector-data-version-2)    | false     |
