---
title: IFillFormat
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 5520
url: /net/aspose.slides/ifillformat/
---
## IFillFormat interface

Represents a fill formatting options.

```csharp
public interface IFillFormat : IFillParamSource
```

## Members

| name | description |
| --- | --- |
| [AsIFillParamSource](asifillparamsource) { get; } | Allows to get base IFillParamSource interface. Read-only [`IFillParamSource`](../ifillparamsource). |
| [FillType](filltype) { get; set; } | Returns or sets the type of filling. Read/write [`FillType`](../filltype). |
| [GradientFormat](gradientformat) { get; } | Returns the gradient fill format. Read-only [`IGradientFormat`](../igradientformat). |
| [PatternFormat](patternformat) { get; } | Returns the pattern fill format. Read-only [`IPatternFormat`](../ipatternformat). |
| [PictureFillFormat](picturefillformat) { get; } | Returns the picture fill format. Read-only [`IPictureFillFormat`](../ipicturefillformat). |
| [RotateWithShape](rotatewithshape) { get; set; } | Determines whether the fill should be rotated with shape. Read/write [`NullableBool`](../nullablebool). |
| [SolidFillColor](solidfillcolor) { get; } | Returns the fill color. Read-only [`IColorFormat`](../icolorformat). |
| [GetEffective](geteffective)() | Gets effective fill formatting data with the inheritance applied. |

### See Also

* interface [IFillParamSource](../ifillparamsource)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->