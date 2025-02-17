---
title: Shape.LockAspectRatio property (Publisher)
keywords: vbapb10.chm2228291
f1_keywords:
- vbapb10.chm2228291
ms.prod: publisher
api_name:
- Publisher.Shape.LockAspectRatio
ms.assetid: eeb87bb5-01d5-5d21-b268-045497ea3682
ms.date: 06/13/2019
ms.localizationpriority: medium
---


# Shape.LockAspectRatio property (Publisher)

Returns or sets an **[MsoTriState](office.msotristate.md)** constant indicating whether the specified shape retains its original proportions when you resize it. Read/write.


## Syntax

_expression_.**LockAspectRatio**

_expression_ A variable that represents a **[Shape](Publisher.Shape.md)** object.


## Remarks

The **LockAspectRatio** property value can be one of the **MsoTriState** constants declared in the Microsoft Office type library and shown in the following table.

|Constant|Description|
|:-----|:-----|
| **msoFalse**|The height and width of the shape change independently of one another when you resize it.|
| **msoTriStateMixed**|A return value indicating a combination of **msoTrue** and **msoFalse** for the specified shape range.|
| **msoTriStateToggle**|A set value that switches between **msoTrue** and **msoFalse**.|
| **msoTrue**|The specified shape retains its original proportions when you resize it.|

## Example

This example adds a cube to the active publication. The cube can be moved and resized, but not reproportioned.

```vb
Dim shp As Shape 
 
Set shp = ActiveDocument.Pages(1).Shapes _ 
 .AddShape(Type:=msoShapeCube, _ 
 Left:=50, Top:=50, Width:=100, Height:=200) _ 
 
shp.LockAspectRatio = msoTrue
```

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]