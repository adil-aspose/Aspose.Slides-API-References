---
title: MinColumnWidth
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 150
url: /net/aspose.slides.mathtext/imathmatrix/mincolumnwidth/
---
## IMathMatrix.MinColumnWidth property

Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0.

```csharp
public uint MinColumnWidth { get; set; }
```

## Examples

Example:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.MinColumnWidth = 20;
```

### See Also

* interface [IMathMatrix](../../imathmatrix)
* namespace [Aspose.Slides.MathText](../../imathmatrix)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->