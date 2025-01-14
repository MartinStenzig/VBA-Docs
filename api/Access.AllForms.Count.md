---
title: AllForms.Count property (Access)
keywords: vbaac10.chm12681
f1_keywords:
- vbaac10.chm12681
ms.prod: access
api_name:
- Access.AllForms.Count
ms.assetid: 1540145e-541d-10fc-249b-9fadc6861a11
ms.date: 02/01/2019
ms.localizationpriority: medium
---


# AllForms.Count property (Access)

Use the **Count** property to determine the number of items in a specified collection. Read-only **Long**.


## Syntax

_expression_.**Count**

_expression_ A variable that represents an **[AllForms](Access.AllForms.md)** object.


## Example

For example, if you want to determine the number of forms currently open or existing on the database, you would use the following code strings.

```vb
' Determine the number of open forms. 
 
forms.count 
 
' Determine the number of forms (open or closed) 
' in the current database. 
 
currentproject.allforms.count

```




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]