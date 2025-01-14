---
title: Window.BeforeWindowPageTurn event (Visio)
keywords: vis_sdr.chm11619080
f1_keywords:
- vis_sdr.chm11619080
ms.prod: visio
api_name:
- Visio.Window.BeforeWindowPageTurn
ms.assetid: 818dd4c6-49bd-37ee-c488-e8e0b33b3968
ms.date: 06/08/2017
ms.localizationpriority: medium
---


# Window.BeforeWindowPageTurn event (Visio)

Occurs before a window is about to show a different page.


## Syntax

_expression_.**BeforeWindowPageTurn** (_Window_)

_expression_ A variable that represents a **[Window](Visio.Window.md)** object.


## Parameters



|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Window_|Required| **[IVWINDOW]**|The window that is going to show a different page.|

## Remarks

If you are using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own **Event** objects, use the **[Add](visio.eventlist.add.md)** or **[AddAdvise](visio.eventlist.addadvise.md)** method. 

To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. 

To create an **Event** object that receives notification, use the **AddAdvise** method. 

To find an event code for the event that you want to create, see [Event codes](../visio/Concepts/event-codesvisio.md).

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]