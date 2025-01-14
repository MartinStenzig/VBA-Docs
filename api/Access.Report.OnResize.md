---
title: Report.OnResize property (Access)
keywords: vbaac10.chm13857
f1_keywords:
- vbaac10.chm13857
ms.prod: access
api_name:
- Access.Report.OnResize
ms.assetid: 336eceb4-7f78-b0b0-cb8f-a6a35c8bea76
ms.date: 03/15/2019
ms.localizationpriority: medium
---


# Report.OnResize property (Access)

Sets or returns the value of the **On Resize** box in the Properties window of a report. Read/write **String**.


## Syntax

_expression_.**OnResize**

_expression_ A variable that represents a **[Report](Access.Report.md)** object.


## Remarks

This property is helpful for programmatically changing the action that Microsoft Access takes when an event is triggered. For example, between event calls you may want to change an expression's parameters, or switch from an event procedure to an expression or macro, depending on the circumstances under which the event was triggered. 

The **Resize** event occurs when a report is opened and whenever the size of a report changes.

The **OnResize** value will be one of the following, depending on the selection chosen in the Choose Builder window (accessed by choosing the **Build** button next to the **On Resize** box in the report's Properties window):

- If you choose Expression Builder, the value will be =_expression_, where _expression_ is the expression from the Expression Builder window.
    
- If you choose Macro Builder, the value is the name of the macro. 
    
- If you choose Code Builder, the value will be [Event Procedure]. 
    
If the **On Resize** box is blank, the property value is an empty string.



[!include[Support and feedback](~/includes/feedback-boilerplate.md)]