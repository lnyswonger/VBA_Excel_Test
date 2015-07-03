
# TextFrame.MarginTop Property (Excel)

Returns or sets the distance (in points) between the top of the text frame and the top of the inscribed rectangle of the shape that contains the text. Read/write  **Single**.


## Syntax

 _expression_. **MarginTop**

 _expression_A variable that represents a  **TextFrame** object.


## Example

This example adds a rectangle to  `myDocument`, adds text to the rectangle, and then sets the margins for the text frame.


```
Set myDocument = Worksheets(1) 
With myDocument.Shapes.AddShape(msoShapeRectangle, _ 
 0, 0, 250, 140).TextFrame 
 .Characters.Text = "Here is some test text" 
 .MarginBottom = 0 
 .MarginLeft = 100 
 .MarginRight = 0 
 .MarginTop = 20 
End With
```


## See also


#### Concepts


 [TextFrame Object](4a6d2201-84b8-d83a-cc13-703da047815e.md)
#### Other resources


 [TextFrame Object Members](299ac22a-bf3d-11ca-90e8-a05d52a760d4.md)
****   **Contribute to this article**Want to edit or suggest changes to this content? You can edit and submit changes to  [this article](https://github.com/jhershey00/VBA_Excel_Test/OpenXMLCon/articles/5c03ceb4-e2fd-9ff7-ac5d-4fad45cd5313.md) using GitHub.

