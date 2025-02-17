---
title: CommandButton.Caption property (Access)
keywords: vbaac10.chm10450
f1_keywords:
- vbaac10.chm10450
ms.prod: access
api_name:
- Access.CommandButton.Caption
ms.assetid: 9141b138-5bf7-5d45-f945-f9de41e43042
ms.date: 03/05/2019
ms.localizationpriority: medium
---


# CommandButton.Caption property (Access)

Gets or sets the text that appears in the control. Read/write **String**.


## Syntax

_expression_.**Caption**

_expression_ A variable that represents a **[CommandButton](Access.CommandButton.md)** object.


## Remarks

The **Caption** property is a string expression that can contain up to 2,048 characters.

The text of the **Caption** property for a label or command button control is the hyperlink display text when the **HyperlinkAddress** or **HyperlinkSubAddress** property is set for the control.

Use the **Caption** property to assign an access key to a label or command button. In the caption, include an ampersand (&) immediately preceding the character that you want to use as an access key. The character will be underlined. You can press Alt plus the underlined character to move the focus to that control on a form.

Include two ampersands (&&) in the setting for a caption if you want to display an ampersand itself in the caption text. For example, to display **Save & Exit**, you should type **Save && Exit** in the **Caption** property box.


[!include[Support and feedback](~/includes/feedback-boilerplate.md)]