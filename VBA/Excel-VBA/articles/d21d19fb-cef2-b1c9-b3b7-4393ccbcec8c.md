
# Watch.Source Property (Excel)

Returns a  **Variant** value that represents the unique name that identifies items that have a **[SourceType](17c41741-1bca-0c07-d113-fd68ba7add75.md)** property value of **xlSourceRange** , **xlSourceChart** , **xlSourcePrintArea** , **xlSourceAutoFilter** , **xlSourcePivotTable** , or **xlSourceQuery** .


## Syntax

 _expression_ . **Source**

 _expression_ A variable that represents a **[Watch](21b84863-55a8-e942-1941-bbe81ec3c7e2.md)** object.


## Remarks

If the  **SourceType** property is set to **xlSourceRange** , this property returns a range, which can be a defined name. If the **SourceType** property is set to **xlSourceChart** , **xlSourcePivotTable** , or **xlSourceQuery** , this property returns the name of the object, such as a chart name, a PivotTable report name, or a query table name.


## See also


#### Concepts


[Watch Object](21b84863-55a8-e942-1941-bbe81ec3c7e2.md)
