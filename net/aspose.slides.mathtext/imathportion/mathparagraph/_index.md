---
title: MathParagraph
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.slides.mathtext/imathportion/mathparagraph/
---
## IMathPortion.MathParagraph property

Math paragraph

```csharp
public IMathParagraph MathParagraph { get; }
```

## Examples

Example:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAutoShape shape = pres.Slides[0].Shapes.AddMathShape(0, 0, 300, 50);
    IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
    mathParagraph.Add(new MathBlock(new MathematicalText("x+y")));
}
```

### See Also

* interface [IMathParagraph](../../imathparagraph)
* interface [IMathPortion](../../imathportion)
* namespace [Aspose.Slides.MathText](../../imathportion)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->