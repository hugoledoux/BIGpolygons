# A few BIG polygons

A few examples of big polygons as found in GIS.
Big here means that they contain several vertices and/or several inner rings (also called holes, or inner boundaries).

They are all publicly available, and are usually polygons reprensenting land cover.

I usually use them to test the capabilities of code I write to process GIS datasets, eg [prepair](https://github.com/tudelft3d/prepair).

The CRS of all the polygons is EPSG:4326 so that they can be visualised direclty here in GitHub (just click on one geojson to view it).

I'd be grateful if you submitted other interesting ones through pull requests.


## Details

| dataset   | total # vertices | # inner rings | # vertices largest ring | source | OGC valid |
| --------- | ----------------:| -------------:| ------------:| ------ |:---------:|
| [cleveland](https://github.com/hugoledoux/BIGpolygons/blob/master/cleveland.geojson) |  1,689,703 |  66,908 |  500,373  | [Cleveland Metroparks](http://clevelandmetroparks.com)                             | false     |
| [EU](https://github.com/hugoledoux/BIGpolygons/blob/master/EU-199948.geojson)        |  1,189,903 |   7,672 |  280,150  | [Corine land cover](http://www.eea.europa.eu/data-and-maps/data/clc-2006-vector-data-version-2)    | false     |
| [russia](https://github.com/hugoledoux/BIGpolygons/blob/master/russia.geojson)       |    283,515 |       0 |  283,515  | [Large Scale International Boundary Lines ](https://hiu.state.gov/data/)           | true      |
| [canada](https://github.com/hugoledoux/BIGpolygons/blob/master/canada.geojson)       |    193,279 |       0 |  193,279  | [Large Scale International Boundary Lines ](https://hiu.state.gov/data/)           | true      |
| [085M](https://github.com/hugoledoux/BIGpolygons/blob/master/085M.geojson)           |    192,355 |   7,684 |   39,067  | [Canada Land Cover](http://www.geobase.ca/geobase/en/data/landcover/index.html)    | false     |
| [EU](https://github.com/hugoledoux/BIGpolygons/blob/master/EU-180927.geojson)        |    102,272 |     299 |   63,346  | [Corine land cover](http://www.eea.europa.eu/data-and-maps/data/clc-2006-vector-data-version-2)    | false     |
| [021L](https://github.com/hugoledoux/BIGpolygons/blob/master/021L.geojson))          |    148,612 |   5,132 |   34,471  | [Canada Land Cover](http://www.geobase.ca/geobase/en/data/landcover/index.html)    | false     |
