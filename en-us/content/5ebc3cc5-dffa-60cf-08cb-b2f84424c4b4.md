
# Workbook.ChangeHistoryDuration Property (Excel)

Returns or sets the number of days shown in the shared workbook's change history. Read/write  **Long**.


## Syntax

 _expression_. **ChangeHistoryDuration**

 _expression_A variable that represents a  **Workbook** object.


## Remarks

Any changes in the change history older than the setting for this property are removed when the workbook is closed.


## Example

This example sets the number of days shown in the change history for the active workbook if change tracking is enabled. Any changes in the change history older than the setting for this property are removed when the workbook is closed.


```
With ActiveWorkbook 
 If .KeepChangeHistory Then 
 .ChangeHistoryDuration = 7 
 End If 
End With
```


## See also


#### Concepts


 [Workbook Object](8c00aa60-c974-eed3-0812-3c9625eb0d4c.md)
#### Other resources


 [Workbook Object Members](dce102a3-25de-3ff4-2ce5-bc56e08baca7.md)
****   **Contribute to this article**Want to edit or suggest changes to this content? You can edit and submit changes to  [this article](https://github.com/jhershey00/VBA_Excel_Test/OpenXMLCon/articles/5ebc3cc5-dffa-60cf-08cb-b2f84424c4b4.md) using GitHub.

