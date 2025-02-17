---
title: UserPermission.UserId property (Office)
keywords: vbaof11.chm260001
f1_keywords:
- vbaof11.chm260001
ms.prod: office
api_name:
- Office.UserPermission.UserId
ms.assetid: 63c7f01b-3b41-6245-7d3f-5c6440703ccf
ms.date: 01/29/2019
ms.localizationpriority: medium
---


# UserPermission.UserId property (Office)

Gets the email name of the user whose permissions on the active document are determined by the specified **UserPermission** object. Read-only.


## Syntax

_expression_.**UserId**

_expression_ A variable that represents a **[UserPermission](Office.UserPermission.md)** object.


## Remarks

The **UserPermission** object associates a set of permissions on the active document with a single user and an optional expiration date. The **UserID** property returns the name in email form of the user whose permissions are determined by the specified **UserPermission** object.


## Example

The following example lists the users who have permissions on the active document.


```vb
 Dim irmPermission As Office.Permission 
 Dim irmUserPerm As Office.UserPermission 
 Dim strUsers As String 
 Set irmPermission = ActiveWorkbook.Permission 
 If irmPermission.Enabled Then 
 For Each irmUserPerm In irmPermission 
 strUsers = strUsers & irmUserPerm.UserId & vbCrLf 
 Next 
 MsgBox strUsers, _ 
 vbInformation + vbOKOnly, "IRM Information" 
 Else 
 MsgBox "Permissions are not enabled for this document.", _ 
 vbInformation + vbOKOnly, "IRM Information" 
 End If 
 Set irmUserPerm = Nothing 
 Set irmPermission = Nothing 

```


## See also

- [UserPermission object members](overview/Library-Reference/userpermission-members-office.md)


[!include[Support and feedback](~/includes/feedback-boilerplate.md)]