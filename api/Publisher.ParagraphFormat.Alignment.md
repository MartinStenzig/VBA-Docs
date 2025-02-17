---
title: ParagraphFormat.Alignment property (Publisher)
keywords: vbapb10.chm5439491
f1_keywords:
- vbapb10.chm5439491
ms.prod: publisher
api_name:
- Publisher.ParagraphFormat.Alignment
ms.assetid: db66f8b8-a813-418c-2735-e5299e6a6045
ms.date: 06/12/2019
ms.localizationpriority: medium
---


# ParagraphFormat.Alignment property (Publisher)

Returns or sets a **[PbParagraphAlignmentType](Publisher.PbParagraphAlignmentType.md)** constant that represents the alignment for the specified paragraphs. Read/write.


## Syntax

_expression_.**Alignment**

_expression_ A variable that represents a **[ParagraphFormat](Publisher.ParagraphFormat.md)** object.


## Remarks

The **Alignment** property value can be one of the **PbParagraphAlignmentType** constants declared in the Microsoft Publisher type library.


## Example

This example adds a new text box to the first page of the active publication, and then adds text and sets the paragraph alignment and font formatting.

```vb
Sub NewTextFrame() 
 Dim shpTextBox As Shape 
 Set shpTextBox = ActiveDocument.Pages(1).Shapes _ 
 .AddTextbox(Orientation:=pbTextOrientationHorizontal, _ 
 Left:=72, Top:=72, Width:=468, Height:=72) 
 With shpTextBox.TextFrame.TextRange 
 .ParagraphFormat.Alignment = pbParagraphAlignmentCenter 
 .Text = "Hello World" 
 With .Font 
 .Name = "Snap ITC" 
 .Size = 30 
 .Bold = msoTrue 
 End With 
 End With 
End Sub
```

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]