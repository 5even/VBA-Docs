---
title: AxisTitle.FormulaR1C1 property (Word)
keywords: vbawd10.chm98238504
f1_keywords:
- vbawd10.chm98238504
ms.prod: word
api_name:
- Word.AxisTitle.FormulaR1C1
ms.assetid: 14c8d64c-ed9b-615f-bd44-a3cc33c26c2f
ms.date: 06/08/2017
ms.localizationpriority: medium
---


# AxisTitle.FormulaR1C1 property (Word)

Returns or sets the formula for the object, using R1C1-style notation in the language of the macro. Read/write **String**.


## Syntax

_expression_.**FormulaR1C1**

_expression_ A variable that represents an '[AxisTitle](Word.AxisTitle.md)' object.


## Remarks

If the cell contains a constant, this property returns the constant. If the cell is empty, the property returns an empty string. If the cell contains a formula, the property returns the formula as a string, in the same format in which it would be displayed in the formula bar (including the equal sign).

If you set the value or formula of a cell to a date, Microsoft Excel checks to see whether that cell is already formatted with one of the date or time number formats. If not, the number format is changed to the default short date number format.

If the range is a one- or two-dimensional range, you can set the formula to a Visual Basic array of the same dimensions. Similarly, you can put the formula into a Visual Basic array.

Setting the formula of a multiple-cell range fills all cells in the range with the formula.


## See also


[AxisTitle Object](Word.AxisTitle.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]