
# OLEDBError.Number Property (Excel)

Returns a numeric value that specifies an error. The error number corresponds to a unique trap number corresponding to an error condition that resulted after the most recent OLE DB query. Read-only  **Long**.


## Syntax

 _expression_. **Number**

 _expression_A variable that represents an  **OLEDBError** object.


## Example

This example displays the error number and other error information returned by the most recent OLE DB query.


```
Set objEr = Application.OLEDBErrors(1) 
MsgBox "The following error occurred:" &amp; _ 
 objEr.Number &amp; ", " &amp; objEr.Native &amp; ", " &amp; _ 
 objEr.ErrorString &amp; " : " &amp; objEr.SqlState
```


## See also


#### Concepts


 [OLEDBError Object](6bcbf721-f2c8-f784-361b-e1a298bb2ecb.md)
#### Other resources


 [OLEDBError Object Members](52181252-dd6f-b267-fa21-4ad8175b7346.md)
****   **Contribute to this article**Want to edit or suggest changes to this content? You can edit and submit changes to  [this article](https://github.com/jhershey00/VBA_Excel_Test/OpenXMLCon/articles/9e88a0bb-1cbf-d98e-52a9-a8f9a0bde81c.md) using GitHub.

