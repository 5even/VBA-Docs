---
title: SubForm.Locked property (Access)
keywords: vbaac10.chm11933
f1_keywords:
- vbaac10.chm11933
ms.prod: access
api_name:
- Access.SubForm.Locked
ms.assetid: 30e0f94d-2a45-7185-1aa9-f0c6f42904c3
ms.date: 02/22/2019
ms.localizationpriority: medium
---


# SubForm.Locked property (Access)

The **Locked** property specifies whether you can edit data in a control in Form view. Read/write **Boolean**.


## Syntax

_expression_.**Locked**

_expression_ A variable that represents a **[SubForm](Access.SubForm.md)** object.


## Remarks

The default setting of the **Locked** property is **True**. This setting allows editing, adding, and deleting data.

Use the **Locked** property to protect data in a field by making it read-only. For example, you might want a control to only display information without allowing editing, or you might want to lock a control until a specific condition is met.


## Example

The following example toggles the **Enabled** property of a command button and the **Enabled** and **Locked** properties of a control, depending on the type of employee displayed in the current record. If the employee is a manager, the **SalaryDetails** button is enabled and the **PersonalInfo** control is unlocked and enabled.

```vb
Sub Form_Current() 
 If Me!EmployeeType = "Manager" Then 
 Me!SalaryDetails.Enabled = True 
 Me!PersonalInfo.Enabled = True 
 Me!PersonalInfo.Locked = False 
 Else 
 Me!SalaryDetails.Enabled = False 
 Me!PersonalInfo.Enabled = False 
 Me!PersonalInfo.Locked = True 
 End If 
End Sub
```


[!include[Support and feedback](~/includes/feedback-boilerplate.md)]