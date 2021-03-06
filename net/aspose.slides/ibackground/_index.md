---
title: IBackground
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 5040
url: /net/aspose.slides/ibackground/
---
## IBackground interface

Represents background of a slide.

```csharp
public interface IBackground : IFillParamSource, ISlideComponent
```

## Members

| name | description |
| --- | --- |
| [AsIFillParamSource](asifillparamsource) { get; } | Returns IFillParamSource interface. Read-only [`IFillParamSource`](../ifillparamsource). |
| [AsISlideComponent](asislidecomponent) { get; } | Returns ISlideComponent interface. Read-only [`ISlideComponent`](../islidecomponent). |
| [EffectFormat](effectformat) { get; } | Returns a EffectFormat for BackgroundType.OwnBackground fill. Read-only [`IEffectFormat`](../ieffectformat). |
| [FillFormat](fillformat) { get; } | Returns a FillFormat for BackgroundType.OwnBackground fill. Read-only [`IFillFormat`](../ifillformat). |
| [StyleColor](stylecolor) { get; } | Returns a ColorFormat for a BackgroundType.Themed fill. Read-only [`IColorFormat`](../icolorformat). |
| [StyleIndex](styleindex) { get; set; } | Returns an index of BackgroundType.Themed fill in background theme collection. 0 means no fill. 1..999 - index. Read/write UInt16. |
| [Type](type) { get; set; } | Returns a type of background fill. Read/write [`BackgroundType`](../backgroundtype). |
| [GetEffective](geteffective)() | Gets effective background data with the inheritance applied. |

### See Also

* interface [IFillParamSource](../ifillparamsource)
* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
