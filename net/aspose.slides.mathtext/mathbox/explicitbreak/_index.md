---
title: ExplicitBreak
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 80
url: /net/aspose.slides.mathtext/mathbox/explicitbreak/
---
## MathBox.ExplicitBreak property

Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break)

```csharp
public byte ExplicitBreak { get; set; }
```

## Examples

Example:

```csharp
[C#]
IMathBox box = new MathematicalText("==").ToBox();
box.ExplicitBreak = 1;
```

### See Also

* class [MathBox](../../mathbox)
* namespace [Aspose.Slides.MathText](../../mathbox)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->