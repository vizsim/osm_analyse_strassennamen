# osm_analyse_strassennamen

Kurze Erklärung und Beispiel für die Extrahierung und Nutzung von größeren OSM-Datensätzen.
(Für keine Bereiche oder seltene Tags würde ich auch weiterhin Overpass empfehlen.)

Der hier beschriebene Ansatz basiert auf dem Tutorial von Hans Hack
https://journocode.com/2018/01/extract-geodata-openstreetmap-osmfilter/

In meinem Beispielcode habe ich jedoch die externen Programme nicht in der Shell sondern direkt in  python/jupyter ausgeführt, was Reproduzierbarkeit etwas vereinfacht und trotzdem die Performance der externen Programme osmconvert und osmfilter nutzt.



### OSM Datenquelle:

https://download.geofabrik.de/europe/germany.html



### Programme:

* osmfilter -> [wiki.openstreetmap.org/wiki/Osmfilter](http://wiki.openstreetmap.org/wiki/Osmfilter)
* osmconvert -> [wiki.openstreetmap.org/wiki/Osmconvert](http://wiki.openstreetmap.org/wiki/Osmconvert)

### python libraries:

* insb. geopandas (darin erhalten auch die nötige gdal)
* http://svn.osgeo.org/gdal/trunk/gdal/swig/python/samples/ogr2ogr.py
  * einfach in ausführenden Ordner legen (sie o.g. Programme)



##  Beispiele :



![](streetnames_plots/plt_Diesel.png)



![](streetnames_plots/plt_Eisenbahn.png)
