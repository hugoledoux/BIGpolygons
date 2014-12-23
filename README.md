# Some crazy polygons

A few examples of 'crazy polygons' as found in GIS.
Crazy here means that they contain several vertices and/or several inner rings (also called holes, or inner boundaries).


The ones here are all publicly available, and are usually polygons reprensenting land cover.
They have been obtained by converting a grid to a vector format.
I usually use them to test the capabilities of code I write to process GIS datasets.

I'd be grateful if you submitted other ones through pull requests.


## Details

| dataset   | total # vertices | # inner rings | source | OGC valid |
| --------- | ----------------:| -------------:| ------ |:---------:|
| cleveland |        1,689,703 |        66,908 | ?    | false     |
| EU-199948 |        1,189,903 |         7,672 | Corine land cover [^corine]    | false     |
| EU-180927 |          102,272 |           299 | Corine land cover [^corine]    | false     |


[^corine]: http://www.eea.europa.eu/data-and-maps/data/clc-2006-vector-data-version-2