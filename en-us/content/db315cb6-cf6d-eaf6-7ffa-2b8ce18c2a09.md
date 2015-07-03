
# WorksheetFunction.IsNA Method (Excel)

Checks the type of value and returns TRUE or FALSE depending if the value refers to the #N/A (value not available) error value.


## Syntax

 _expression_. **IsNA**( **_Arg1_**)

 _expression_A variable that represents a  **WorksheetFunction** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
|Arg1|Required| **Variant**|Value - the value you want tested. Value can be a blank (empty cell), error, logical, text, number, or reference value, or a name referring to any of these, that you want to test.|

### Return Value

Boolean


## Remarks




- The value arguments of the IS functions are not converted. For example, in most other functions where a number is required, the text value "19" is converted to the number 19. However, in the formula ISNUMBER("19"), "19" is not converted from a text value, and the ISNUMBER function returns FALSE.
    
- The IS functions are useful in formulas for testing the outcome of a calculation. When combined with the IF function, they provide a method for locating errors in formulas (see the following examples).
    

## See also


#### Concepts


 [WorksheetFunction Object](7b1d5639-363d-632c-2cf0-2232562646b6.md)
#### Other resources


 [WorksheetFunction Object Members](6811ca87-4b53-0bff-88c9-30bf7497879a.md)
****   **Contribute to this article**Want to edit or suggest changes to this content? You can edit and submit changes to  [this article](https://github.com/jhershey00/VBA_Excel_Test/OpenXMLCon/articles/db315cb6-cf6d-eaf6-7ffa-2b8ce18c2a09.md) using GitHub.

