
# PivotField.CurrentPageName Property (Excel)

Returns or sets the currently displayed page of the specified PivotTable report. The name of the page appears in the page field. Note that this property works only if the currently displayed page already exists. Read/write  **String**.


## Syntax

 _expression_. **CurrentPageName**

 _expression_A variable that represents a  **PivotField** object.


## Remarks

This property applies to PivotTables that are connected to an OLAP data source. Attempting to return or set this property with a PivotTable that is not connected to an OLAP data source will result in a run-time error.


## Example

This example sets the name of the currently displayed page of the first PivotTable report on the active worksheet to "USA."


```
ActiveSheet.PivotTables("PivotTable1") _ 
 .PivotFields("[Customers]").CurrentPageName = _ 
 "[Customers].[All Customers].[USA]"
```


## See also


#### Concepts


 [PivotField Object](52784960-e2da-b43a-1e37-2d4dae61c6d8.md)
#### Other resources


 [PivotField Object Members](4a6ea12a-072c-a386-c855-7bf5f6eadd46.md)
****   **Contribute to this article**Want to edit or suggest changes to this content? You can edit and submit changes to  [this article](https://github.com/jhershey00/VBA_Excel_Test/OpenXMLCon/articles/cdf3be5e-d71b-af73-e65b-63075b78bfeb.md) using GitHub.

