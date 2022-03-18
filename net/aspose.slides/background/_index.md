---
title: Background
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 840
url: /net/aspose.slides/background/
---
## Background class

Represents background of a slide.

```csharp
public class Background : PVIObject, IBackground
```

## Public Members

| name | description |
| --- | --- |
| [EffectFormat](effectformat) { get; } | Returns a EffectFormat for BackgroundType.OwnBackground fill. Read-only [`IEffectFormat`](../ieffectformat). |
| [FillFormat](fillformat) { get; } | Returns a FillFormat for BackgroundType.OwnBackground fill. Read-only [`IFillFormat`](../ifillformat). |
| [Presentation](presentation) { get; } | Returns the parent presentation of a slide. Read-only [`IPresentation`](../ipresentation). |
| [Slide](slide) { get; } | Returns the parent slide of a shape. Read-only [`IBaseSlide`](../ibaseslide). |
| [StyleColor](stylecolor) { get; } | Return a ColorFormat for a BackgroundType.Themed fill. Read-only [`IColorFormat`](../icolorformat). |
| [StyleIndex](styleindex) { get; set; } | Returns an index of BackgroundType.Themed fill in background theme collection. 0 means no fill. 1..999 - index. Read/write UInt16. |
| [Type](type) { get; set; } | Returns a type of background fill. Read/write [`BackgroundType`](../backgroundtype). |
| [GetEffective](geteffective)() | Gets effective background data with the inheritance applied. |

### See Also

* class [PVIObject](../pviobject)
* interface [IBackground](../ibackground)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->