# Manifold® Release 9 programming basics
This repo is a community effort to provide additional documents and samples about coding in Manifold® Release 9.
### Never heard of Manifold® Release 9?
Manifold® Release 9 or Manifold® System Release 9, often referred to as Manifold 9, Release 9 or **M9**, for short, is a desktop GIS package like ArcGIS, Global Mapper, FME, MapInfo, and QGIS. We, here, think that **M9** surpasses the others in various ways.
 

**M9** has a sister product called SQL for ArcGIS® Pro (aka **sql4arc**), which is basically **M9**, just tightly integrated with and packaged as ArcGIS® Pro add-in.
The information here appies to **sql4arc** as well and, to a lesser extent, to Manifold Viewer which is read-only version of **M9**. Viewer cannot run .NET scripts, but has full SQL capabilities. 

## .NET API of M9
Official documentation is available [here](https://manifold.net/doc/api/scripts-net.html ".NET API").

Document ["Obtains"](https://github.com/rkolka/Manifold-9-programming-basics/blob/master/obtains.md), or which type of objects can a class/object return. 
* Eg. a `Command` object can, among other things, return a `Table` (when `Run` is called).

Document ["Obtained from"](https://github.com/rkolka/Manifold-9-programming-basics/blob/master/obtained_from.md), or from which class/object can be obtained from. 
* Eg. a `CoordSet` object can be, among others, obtained from a `Geom` object (by calling `Coords`).

## SQL of M9
Official documentation is available [here](https://manifold.net/doc/mfd9/sql.htm "SQL").

[*More coming soon*]
