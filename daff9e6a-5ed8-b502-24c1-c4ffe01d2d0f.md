
# WorksheetFunction.RoundUp Method (Excel)

Rounds a number up, away from 0 (zero).


## Syntax

 _expression_. **RoundUp**( **_Arg1_**,  **_Arg2_**)

 _expression_A variable that represents a  **WorksheetFunction** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
|Arg1|Required| **Double**|Number - any real number that you want rounded up.|
|Arg2|Required| **Double**|Num_digits - the number of digits to which you want to round number.|

### Return Value

Double


## Remarks




- ROUNDUP behaves like ROUND, except that it always rounds a number up.
    
- If num_digits is greater than 0 (zero), then number is rounded up to the specified number of decimal places.
    
- If num_digits is 0, then number is rounded up to the nearest integer.
    
- If num_digits is less than 0, then number is rounded up to the left of the decimal point.
    

## See also


#### Concepts


 [WorksheetFunction Object](7b1d5639-363d-632c-2cf0-2232562646b6.md)
#### Other resources


 [WorksheetFunction Object Members](6811ca87-4b53-0bff-88c9-30bf7497879a.md)
****   **Contribute to this article**Want to edit or suggest changes to this content? You can edit and submit changes to  [this article](https://github.com/jhershey00/VBA_Excel_Test/OpenXMLCon/articles/daff9e6a-5ed8-b502-24c1-c4ffe01d2d0f.md) using GitHub.

