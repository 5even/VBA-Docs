---
title: BoundObjectFrame.BackShade property (Access)
keywords: vbaac10.chm14633
f1_keywords:
- vbaac10.chm14633
ms.prod: access
api_name:
- Access.BoundObjectFrame.BackShade
ms.assetid: 17c2e087-d4c7-f27d-a3a0-01470aa2b348
ms.date: 02/08/2019
ms.localizationpriority: medium
---


# BoundObjectFrame.BackShade property (Access)

Gets or sets the shade that is applied to the theme color in the **[BackColor](access.boundobjectframe.backcolor.md)** property of the specified object. Read/write **Single**.


## Syntax

_expression_.**BackShade**

_expression_ A variable that represents a **[BoundObjectFrame](Access.BoundObjectFrame.md)** object.


## Remarks

The **BackShade** property contains a numeric expression that can be used to darken the theme color in the **BackColor** property. The default value of the **BackShade** property is 100, which is neutral, and does not change the theme color. 

To darken the color, first determine the percentage by which to darken from 1 to 100, and then subtract that value as a whole number from 100 and use the remainder. For example, to darken the theme color by 75%, subtract 75 from 100 and use the remainder, which is 25.

This property is not surfaced in the property sheet.


## Example

The following code example darkens the **BackColor** property by 75%.

```vb
Me.ctl.BackShade=25
```


[!include[Support and feedback](~/includes/feedback-boilerplate.md)]