---
title: CellRange.Count property (PowerPoint)
ms.prod: powerpoint
api_name:
- PowerPoint.CellRange.Count
ms.assetid: 9f81da2d-1b5d-9650-0631-19319dcc4bc0
ms.date: 06/08/2017
ms.localizationpriority: medium
---


# CellRange.Count property (PowerPoint)

Returns the number of objects in the specified collection. Read-only.


## Syntax

_expression_.**Count**

_expression_ A variable that represents a [CellRange](PowerPoint.CellRange.md) object.


## Return value

Long


## Example

This example closes all windows except the active window.


```vb
With Application.Windows

    For i = 2 To .Count

        .Item(2).Close

    Next

End With
```


## See also


[CellRange Object](PowerPoint.CellRange.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]