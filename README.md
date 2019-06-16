# GeoJsonToSTL
Simple web page converter from Geojson to STL specificly for 3D printing.

## fetures

* Height select
  Allows selecting property within the GeoJson as a height veriable. Not selecting anything will result in a height of 2mm.

  This is currently the only way to specify the height at some point would be nice to add suport for coordinates 
  with a (z axis + offset). 

* Group by
  Selecting a property here shall inform how to structure the folder that shall be generated. It will place each shape 
  into a folder using the value of the selected property. 

  Not selecting will put all the shapes into a folder names undefined 
  (plan to make a default folder or just not have a folder when unselected)


* Tolerance
Ability to add a tolerance to a shape by pulling every vertex into the shape. (This method needs a little work for
very acute angles the method can cross points resulting in a broken render.)


To use the tool go to <https://www.seanborg.tech/geojson-to-stl> 
