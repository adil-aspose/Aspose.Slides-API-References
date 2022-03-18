---
title: Base
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.slides.mathtext/imathleftsubsuperscriptelement/base/
---
## IMathLeftSubSuperscriptElement.Base property

Base argument

```csharp
public IMathElement Base { get; }
```

## Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
IMathElement baseElem = leftSubSuperscript.Base;
```

### See Also

* interface [IMathElement](../../imathelement)
* interface [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement)
* namespace [Aspose.Slides.MathText](../../imathleftsubsuperscriptelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->