---
title: CodeProject.CloseConnection method (Access)
keywords: vbaac10.chm12716
f1_keywords:
- vbaac10.chm12716
ms.prod: access
api_name:
- Access.CodeProject.CloseConnection
ms.assetid: 850a09c8-45a8-26e4-79f5-e688599a990a
ms.date: 02/27/2019
ms.localizationpriority: medium
---


# CodeProject.CloseConnection method (Access)

Use the **CloseConnection** method to close the current connection between the **CodeProject** object in a Microsoft Access project (.adp) or Access database and the database specified in the project's base connection string.


## Syntax

_expression_.**CloseConnection**

_expression_ A variable that represents a **[CodeProject](Access.CodeProject.md)** object.


## Return value

Nothing


## Remarks

The **CloseConnection** method closes the current connection of the Access project, database, or data source control, frees the ADO **Connection** object, and sets the **Connection** property to **Null**. The **BaseConnectionString** property is left unchanged. Users are prevented from calling _datasourcecontrol_.Connection.Close and must use this method instead.

The **CloseConnection** method is useful when you have opened a Microsoft Access database from another application through Automation.




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]