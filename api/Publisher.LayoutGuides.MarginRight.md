---
title: LayoutGuides.MarginRight property (Publisher)
keywords: vbapb10.chm1114117
f1_keywords:
- vbapb10.chm1114117
ms.prod: publisher
api_name:
- Publisher.LayoutGuides.MarginRight
ms.assetid: 5dbfc999-59d6-c9d0-4d9d-bc1a4ee622aa
ms.date: 06/08/2019
ms.localizationpriority: medium
---


# LayoutGuides.MarginRight property (Publisher)

Returns or sets a **Variant** that represents the amount of space (in [points](../language/glossary/vbe-glossary.md#point)) between the text and the right edge of a cell, text frame, or page. Read/write.


## Syntax

_expression_.**MarginRight**

_expression_ A variable that represents a **[LayoutGuides](Publisher.LayoutGuides.md)** object.


## Example

This example sets the margins of the active publication to two inches.

```vb
Sub SetPageMargins() 
 
 With ActiveDocument.LayoutGuides 
 .MarginTop = Application.InchesToPoints(Value:=2) 
 .MarginBottom = Application.InchesToPoints(Value:=2) 
 .MarginLeft = Application.InchesToPoints(Value:=2) 
 .MarginRight = Application.InchesToPoints(Value:=2) 
 End With 
 
End Sub
```

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]