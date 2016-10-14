# How togeojson.js is structured? :sparkles:

* Define a new package name __toGeoJson__
* Some `var` to use in 2 main functions: `toGeoJSON.kml(doc)` and `toGeoJSON.gpx(doc)`
  * `removeSpace` :question:
  * `serializer` :question:
* And some global functions
  * `okhash(x)` generates a short, numeric hash of a string :question:
  * `get(x,y)` get all Y children of X :question:
  * `attr(x,y)` :question:
  * `attrf(x, y)` :question:
  * `get1(x, y)` :question:
  * `norm(el)` :question:
  * `numarray(x)` :question:
  * `clean(x)` :question:
  * `nodeVal(x)` :question:
  * `coord1(v)` :question:
  * `coord(v)` :question:
  * `coordPair(x)` :question:
  * `fc()` :question:
  * `xml2str(str)` :question:
* Define a variable `t` with 2 attribute(class:question:): `kml` and `gpx`
  * `kml` class define some functions:
   * `kmlColor(v)` :question:
   * `gxCoord(v)` :question:
   * `gxCoords(root)` :question:
   * `getGeometry(root)` :question:
   * `getPlacemark(root)` :question:
  * `gpx` class define some functions:
   * `getPoints(node, pointname)` :question:
   * `getTrack(node)` :question:
   * `getRoute(node)` :question:
   * `getPoint(node)` :question:
   * `getProperties(node)` :question:
