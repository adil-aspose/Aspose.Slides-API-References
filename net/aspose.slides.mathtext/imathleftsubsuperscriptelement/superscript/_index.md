---
title: Superscript
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 30
url: /net/aspose.slides.mathtext/imathleftsubsuperscriptelement/superscript/
---
## IMathLeftSubSuperscriptElement.Superscript property

Superscript

```csharp
public IMathElement Superscript { get; }
```

## Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
IMathElement sup = leftSubSuperscript.Superscript;
```

### See Also

* interface [IMathElement](../../imathelement)
* interface [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement)
* namespace [Aspose.Slides.MathText](../../imathleftsubsuperscriptelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->