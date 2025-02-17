---
title: Selection.VisualBoundingBox method (Visio)
ms.assetid: ae107bd8-ac99-6303-2820-a5afb19165a3
ms.date: 06/08/2017
ms.prod: visio
ms.localizationpriority: medium
---


# Selection.VisualBoundingBox method (Visio)

Returns the bounding rectangle of the virtual container that has all the shapes of the given selection. Introduced in Office 2016.


## Syntax

_expression_.**VisualBoundingBox** (_Flags_, _lpr8Left_, _lpr8Bottom_, _lpr8Right_, _lpr8Top_)

_expression_ A variable that represents a **[Selection](Visio.Selection.md)** object.


## Parameters

|Name|Optional/Requires|Data Type|Description|
|:-----|:-----|:-----|:-----|
| _Flags_|Required|INT16|A **[VisBoundingBoxArgs](Visio.visboundingboxargs.md)** constant that describes the returned rectangle.|
| _lpr8Left_|Required|DOUBLE|Left position values for the virtual bounding box.|
| _lpr8Bottom_|Required|DOUBLE|Bottom position values for the virtual bounding box.|
| _lpr8Right_|Required|DOUBLE|Right position values for the virtual bounding box.|
| _lpr8Top_|Required|DOUBLE|Top position values for the virtual bounding box.|

## Return value

**VOID**




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]