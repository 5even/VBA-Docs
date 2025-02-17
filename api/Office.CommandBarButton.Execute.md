---
title: CommandBarButton.Execute method (Office)
ms.prod: office
api_name:
- Office.CommandBarButton.Execute
ms.assetid: 1cf36559-86ba-8a9c-ef81-ef72185dd21c
ms.date: 01/03/2019
ms.localizationpriority: medium
---


# CommandBarButton.Execute method (Office)

Runs the procedure or built-in command assigned to the specified **CommandBarButton** control.

> [!NOTE]
> The use of CommandBars in some Microsoft Office applications has been superseded by the new ribbon component of the Microsoft Office Fluent user interface. For more information, see [Overview of the Office Fluent ribbon](../library-reference/concepts/overview-of-the-office-fluent-ribbon.md).


## Syntax

_expression_.**Execute**

_expression_ Required. A variable that represents a **[CommandBarButton](Office.CommandBarButton.md)** object.


## Example

This Microsoft Excel example creates a command bar and then adds a built-in command bar button control to it. The button executes the Excel **AutoSum** function. This example uses the **Execute** method to total the selected range of cells when the command bar appears.


```vb
Dim cbrCustBar As CommandBar 
Dim ctlAutoSum As CommandBarButton 
Set cbrCustBar = CommandBars.Add("Custom") 
Set ctlAutoSum = cbrCustBar.Controls _ 
    .Add(msoControlButton, CommandBars("Standard") _ 
    .Controls("AutoSum").Id) 
cbrCustBar.Visible = True  
ctlAutoSum.Execute
```


## See also

- [CommandBarButton object members](overview/library-reference/commandbarbutton-members-office.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]