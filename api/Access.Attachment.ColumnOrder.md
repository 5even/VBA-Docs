---
title: Attachment.ColumnOrder property (Access)
keywords: vbaac10.chm14009
f1_keywords:
- vbaac10.chm14009
ms.prod: access
api_name:
- Access.Attachment.ColumnOrder
ms.assetid: e11872da-df82-83e0-0c6f-8716989622dd
ms.date: 02/07/2019
ms.localizationpriority: medium
---


# Attachment.ColumnOrder property (Access)

Use the **ColumnOrder** property to specify the order of the columns in Datasheet view. Read/write **Integer**.


## Syntax

_expression_.**ColumnOrder**

_expression_ A variable that represents an **[Attachment](Access.Attachment.md)** object.


## Remarks

The **ColumnOrder** property applies to all fields in Datasheet view and to form controls when the form is in Datasheet view.

In other views, the property setting is 0 unless you explicitly change the order of one or more fields in Datasheet view (either by dragging the fields to new positions or by changing their **ColumnOrder** property settings). Fields to the right of the moved field's new position will have a property setting of 0 in views other than Datasheet view.

The order of the fields in Datasheet view doesn't affect the order of the fields in table Design view or Form view.

The **ColumnOrder** property isn't available in Design view.


[!include[Support and feedback](~/includes/feedback-boilerplate.md)]