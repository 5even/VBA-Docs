---
title: InvisibleApp.WindowActivated event (Visio)
ms.prod: visio
api_name:
- Visio.InvisibleApp.WindowActivated
ms.assetid: 8ed197e5-945b-aab1-d90d-ed5c448937ce
ms.date: 06/08/2017
ms.localizationpriority: medium
---


# InvisibleApp.WindowActivated event (Visio)

Occurs after the active window changes in a Microsoft Visio instance.


## Syntax

_expression_.**WindowActivated** (_Window_)

_expression_ A variable that represents an **[InvisibleApp](Visio.InvisibleApp.md)** object.


## Parameters



|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Window_|Required| **[IVWINDOW]**|The window that was activated.|

## Remarks

The **WindowActivated** event indicates that the active window has changed in a Visio instance. This event implies that the **ActiveDocument** and **ActivePage** properties of the **Application** object may also have changed; in contrast, any time the **ActiveDocument** or **ActivePage** property changes, a **WindowActivated** event is always generated.

If you are using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own **Event** objects, use the **[Add](visio.eventlist.add.md)** or **[AddAdvise](visio.eventlist.addadvise.md)** method. 

To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. 

To create an **Event** object that receives notification, use the **AddAdvise** method. 

To find an event code for the event that you want to create, see [Event codes](../visio/Concepts/event-codesvisio.md).

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]