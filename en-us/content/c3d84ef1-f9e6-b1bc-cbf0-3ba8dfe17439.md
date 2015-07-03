
# PivotCache Object (Excel)

Represents the memory cache for a PivotTable report.


## Remarks

 The **PivotCache** object is a member of the ** [PivotCaches](cfd979b9-d52f-f34b-4b66-4fb17efcdc92.md)** collection.


## Example

Use the  ** [PivotCache](82602154-783d-3f78-b354-0dabfdc34c98.md)** method to return a **PivotCache** object for a PivotTable report (each report has only one cache). The following example causes the first PivotTable report on the first worksheet to refresh itself whenever its file is opened.


```
Worksheets(1).PivotTables(1).PivotCache.RefreshOnFileOpen = True
```

Use  ** [PivotCaches](0a2e7f10-c123-5c98-fb71-56868b9f8bde.md)**( _index_), where  _index_ is the PivotTable cache number, to return a single **PivotCache** object from the **PivotCaches** collection for a workbook. The following example refreshes cache one.




```
ActiveWorkbook.PivotCaches(1).Refresh
```


## See also


#### Concepts


 [Excel Object Model Reference](11ea8598-8a20-92d5-f98b-0da04263bf2c.md)
#### Other resources


 [PivotCache Object Members](113f1109-e1c9-2c6e-0581-9fba82f278dc.md)
****   **Contribute to this article**Want to edit or suggest changes to this content? You can edit and submit changes to  [this article](https://github.com/jhershey00/VBA_Excel_Test/OpenXMLCon/articles/c3d84ef1-f9e6-b1bc-cbf0-3ba8dfe17439.md) using GitHub.

