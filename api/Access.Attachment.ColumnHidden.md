---
title: Attachment.ColumnHidden property (Access)
keywords: vbaac10.chm14010
f1_keywords:
- vbaac10.chm14010
ms.prod: access
api_name:
- Access.Attachment.ColumnHidden
ms.assetid: 772c644e-b180-25ad-5566-c0b5dc6dbc41
ms.date: 02/07/2019
ms.localizationpriority: medium
---


# Attachment.ColumnHidden property (Access)

Use the **ColumnHidden** property to show or hide a specified column in Datasheet view. Read/write **Boolean**.


## Syntax

_expression_.**ColumnHidden**

_expression_ A variable that represents an **[Attachment](Access.Attachment.md)** object.


## Remarks

The **ColumnHidden** property applies to all fields in Datasheet view and to form controls when the form is in Datasheet view.

Hiding a column with the **ColumnHidden** property in Datasheet view doesn't hide fields from the same column in Form view. Similarly, setting a control's **Visible** property to **False** in Form view doesn't hide the corresponding column in Datasheet view.

The **ColumnHidden** property is not available in Design view.




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]