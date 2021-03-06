---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 6960
url: /net/aspose.slides/itextframeformateffectivedata/
---
## ITextFrameFormatEffectiveData interface

Immutable object which contains effective text frame formatting properties.

```csharp
public interface ITextFrameFormatEffectiveData
```

## Members

| name | description |
| --- | --- |
| [AnchoringType](anchoringtype) { get; } | Returns vertical anchor text in a TextFrame. Read-only [`TextAnchorType`](../textanchortype). |
| [AutofitType](autofittype) { get; } | Returns text autofit mode. Read-only [`TextAutofitType`](../textautofittype). |
| [CenterText](centertext) { get; } | Returns if text should be centered in box horizontally. Read-only Boolean. |
| [ColumnCount](columncount) { get; } | Specifies the number of columns of text in the bounding rectangle. Read-only Int32. |
| [ColumnSpacing](columnspacing) { get; } | Specifies the space between text columns in the text area (in points). Read-only Single. |
| [MarginBottom](marginbottom) { get; } | Returns the bottom margin (points) in a TextFrame. Read-only Double. |
| [MarginLeft](marginleft) { get; } | Returns the left margin (points) in a TextFrame. Read-only Double. |
| [MarginRight](marginright) { get; } | Returns the right margin (points) in a TextFrame. Read-only Double. |
| [MarginTop](margintop) { get; } | Returns the top margin (points) in a TextFrame. Read-only Double. |
| [TextStyle](textstyle) { get; } | Returns effective text's style. Read-only [`ITextStyleEffectiveData`](../itextstyleeffectivedata). |
| [TextVerticalType](textverticaltype) { get; } | Returns text orientation. Read-only [`TextVerticalType`](../textverticaltype). |
| [WrapText](wraptext) { get; } | Returns if text is wrapped at TextFrame's margins. Read-only Boolean. |

## Remarks

This interface is used together with the [`ITextFrameFormat`](../itextframeformat) interface to return effective formatting values with inheritance applied.

### See Also

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
