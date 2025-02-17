---
title: ComboBox.DecimalPlaces property (Access)
keywords: vbaac10.chm11376
f1_keywords:
- vbaac10.chm11376
ms.prod: access
api_name:
- Access.ComboBox.DecimalPlaces
ms.assetid: 5d57d9b7-12bd-2555-242e-204fd8dd48be
ms.date: 03/01/2019
ms.localizationpriority: medium
---


# ComboBox.DecimalPlaces property (Access)

Use the **DecimalPlaces** property to specify the number of decimal places that Microsoft Access uses to display numbers. Read/write **Byte**.


## Syntax

_expression_.**DecimalPlaces**

_expression_ A variable that represents a **[ComboBox](Access.ComboBox.md)** object.


## Remarks

The **DecimalPlaces** property uses the following settings.

|Setting|Visual Basic|Description|
|:-----|:-----|:-----|
|Auto|255|(Default) Numbers appear as specified by the **Format** property setting.|
|0 to 15|0 to 15|Digits to the right of the decimal separator appear with the specified number of decimal places.<br/><br/>Digits to the left of the decimal separator appear as specified by the **Format** property setting.|

You should set the **DecimalPlaces** property in the table's property sheet. A bound control that you create on a form or report inherits the **DecimalPlaces** property set in the field in the underlying table or query, so you won't have to specify the property individually for every bound control that you create.

The **DecimalPlaces** property setting has no effect if the **Format** property is blank or is set to General Number.

The **DecimalPlaces** property affects only the number of decimal places that display, not how many decimal places are stored. To change the way that a number is stored, you must change the **FieldSize** property in table Design view.

Use the **DecimalPlaces** property to display numbers differently from the **Format** property setting or from the way that they are stored. For example, the Currency setting of the **Format** property displays only two decimal places ($5.35). To display Currency numbers with four decimal places (for example, $5.3523), set the **DecimalPlaces** property to 4.


[!include[Support and feedback](~/includes/feedback-boilerplate.md)]