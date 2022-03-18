---
title: MathPortion
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 8440
url: /net/aspose.slides.mathtext/mathportion/
---
## MathPortion class

Represents a portion with mathematical context inside.

```csharp
public sealed class MathPortion : Portion, IMathPortion
```

## Public Members

| name | description |
| --- | --- |
| [MathPortion](mathportion)() | Initializes a new instance of the MathPortion class. |
| [MathParagraph](mathparagraph) { get; } | Math paragraph |

## Examples

Example:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAutoShape shape = pres.Slides[0].Shapes.AddMathShape(0, 0, 300, 50);
    IParagraph paragraph = shape.TextFrame.Paragraphs[0];
    MathPortion mathPortion = new MathPortion();
    paragraph.Portions.Add(mathPortion);
}
```

### See Also

* class [Portion](../../aspose.slides/portion)
* interface [IMathPortion](../imathportion)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->