---
title: Duotone
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 2900
url: /net/aspose.slides.effects/duotone/
---
## Duotone class

Represents a Duotone effect. For each pixel, combines Color1 and Color2 through a linear interpolation to determine the new color for that pixel.

```csharp
public class Duotone : ImageTransformOperation, IDuotone
```

## Public Members

| name | description |
| --- | --- |
| [Color1](color1) { get; } | Returns target color format for dark pixels. Read-only [`IColorFormat`](../../aspose.slides/icolorformat). |
| [Color2](color2) { get; } | Returns target color format for light pixels. Read-only [`IColorFormat`](../../aspose.slides/icolorformat). |
| override [Equals](equals)(…) | Determines whether the specified [`Duotone`](../duotone) is equal to the current [`Duotone`](../duotone). |
| [GetEffective](geteffective)() | Gets effective Duotone effect data with the inheritance applied. |
| override [GetHashCode](gethashcode)() | Serves as a hash function for a particular type. |

### See Also

* class [ImageTransformOperation](../imagetransformoperation)
* interface [IDuotone](../iduotone)
* namespace [Aspose.Slides.Effects](../../aspose.slides.effects)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
