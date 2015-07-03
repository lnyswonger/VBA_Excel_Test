
# Point Object

 **Last modified:** June 30, 2011

 _**Applies to:** Excel 2013 | Office 2013 | VBA_

Represents a single point in a series on the specified chart. The  **Point** object is a member of the ** [Points](b41c8f08-880e-1f4a-0456-3f77c0741bc6.md)**collection, which contains all the points in the specified series.


## Using the Point Object

Use  **Points**( _index_), where  _index_ is the point's index number, to return a single **Point** object. Points are numbered from left to right in the series. `Points(1)` is the leftmost point, and is the leftmost point, and `Points(Points.Count)` is the rightmost point. The following example sets the marker style for the third point in series one. For this example to work, series one must be a 2-D line, scatter, or radar series.


```
myChart.SeriesCollection(1).Points(3).MarkerStyle = xlDiamond
```


****   **Contribute to this article**Want to edit or suggest changes to this content? You can edit and submit changes to  [this article](https://github.com/jhershey00/VBA_Excel_Test/OpenXMLCon/articles/944d5edb-b1e7-7aed-5ead-bde3878b26e5.md) using GitHub.

