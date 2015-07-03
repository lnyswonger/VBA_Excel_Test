
# Axis.TickLabels Property (Excel)

Returns a  ** [TickLabels](fcb02bc5-fcdc-db32-168b-2d40e5552991.md)**object that represents the tick-mark labels for the specified axis. Read-only.


## Syntax

 _expression_. **TickLabels**

 _expression_A variable that represents an  **Axis** object.


## Example

This example sets the color of the tick-mark label font for the value axis in Chart1.


```
Charts("Chart1").Axes(xlValue).TickLabels.Font.ColorIndex = 3
```


## See also


#### Concepts


 [Axis Object](7e08c61b-90f4-8d91-0ee2-84283d10b324.md)
#### Other resources


 [Axis Object Members](2b60f79e-339d-a6cf-7ec6-a915b550c634.md)
****   **Contribute to this article**Want to edit or suggest changes to this content? You can edit and submit changes to  [this article](https://github.com/jhershey00/VBA_Excel_Test/OpenXMLCon/articles/e8a6edf9-2fdd-d8e9-0de9-5c4aa921c6b1.md) using GitHub.
