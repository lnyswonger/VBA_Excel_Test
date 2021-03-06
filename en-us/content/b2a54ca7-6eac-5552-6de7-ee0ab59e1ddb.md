
# MajorUnitScale Property

 **Last modified:** March 09, 2015

 _**Applies to:** Excel 2013 | Office 2013 | VBA_

Returns or sets the major unit scale value for the category axis when the CategoryType property is set to xlTimeScale. Read/write XlTimeUnit .



|XlTimeUnit can be one of these XlTimeUnit constants.|
| **xlDays**|
| **xlMonths**|
| **xlYears**|
 _expression_. **MajorUnitScale**
 _expression_ Required. An expression that returns one of the objects in the Applies To list.

## Example

This example sets the category axis to use a time scale and sets the major and minor units.


```
With myChart.Axes(xlCategory) 
 .CategoryType = xlTimeScale 
 .MajorUnit = 5 
 .MajorUnitScale = xlDays 
 .MinorUnit = 1 
 .MinorUnitScale = xlDays 
End With
```


****   **Contribute to this article**Want to edit or suggest changes to this content? You can edit and submit changes to  [this article](https://github.com/jhershey00/VBA_Excel_Test/OpenXMLCon/articles/b2a54ca7-6eac-5552-6de7-ee0ab59e1ddb.md) using GitHub.

