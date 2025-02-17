---
title: Section.EventProcPrefix property (Access)
keywords: vbaac10.chm12190
f1_keywords:
- vbaac10.chm12190
ms.prod: access
api_name:
- Access.Section.EventProcPrefix
ms.assetid: 4e5b06ef-b3aa-d0c5-002f-dabedd25ec32
ms.date: 02/21/2019
ms.localizationpriority: medium
---


# Section.EventProcPrefix property (Access)

Gets or sets the prefix portion of an event procedure name. Read/write **String**.


## Syntax

_expression_.**EventProcPrefix**

_expression_ A variable that represents a **[Section](Access.Section.md)** object.


## Remarks

For example, if you have a command button with an event procedure named **Details_Click**, the **EventProcPrefix** property returns the string **Details**.

Microsoft Access adds the prefix portion of an event procedure name to the event name with an underscore character ( _ ).




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]