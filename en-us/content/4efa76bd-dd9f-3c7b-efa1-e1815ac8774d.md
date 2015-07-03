
# Application.WorkbookAfterSave Event (Excel)

Occurs after the workbook is saved.


## Version Information

Version Added: Excel 2010 


## Syntax

 _expression_. **WorkbookAfterSave**( **_Wb_**,  **_Success_**)

 _expression_A variable that represents an  ** [Application](19b73597-5cf9-4f56-8227-b5211f657f6f.md)** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
|Wb|Required| ** [Workbook](8c00aa60-c974-eed3-0812-3c9625eb0d4c.md)**|The workbook being saved.|
|Success|Required| **Boolean**|Returns  **True** if the save operation was successful; otherwise **False**.|

### Return Value

Nothing


## Example

The following code example displays a message box if the workbook was successfully saved. This code must be placed in a class module and an instance of that class must be correctly initialized. For more information about how to use event procedures with the  **Application** object, see [Using Events with the Application Object](0063feba-47fd-29be-d2d5-8fcf47e70cbc.md).


```
Private Sub App_WorkbookAfterSave(ByVal Wb As Workbook, _ 
 ByVal Success As Boolean) 
If Success Then 
 MsgBox ("The " &amp; Wb.Name &amp; " workbook was successfully saved.") 
End If 
End Sub
```


## See also


#### Concepts


 [Application Object](19b73597-5cf9-4f56-8227-b5211f657f6f.md)
#### Other resources


 [Application Object Members](4cb9ca42-8d07-cc9c-2d80-4eb9a5921e1e.md)
****   **Contribute to this article**Want to edit or suggest changes to this content? You can edit and submit changes to  [this article](https://github.com/jhershey00/VBA_Excel_Test/OpenXMLCon/articles/4efa76bd-dd9f-3c7b-efa1-e1815ac8774d.md) using GitHub.

