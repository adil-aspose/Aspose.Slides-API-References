---
title: IMathLeftSubSuperscriptElement
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 7840
url: /net/aspose.slides.mathtext/imathleftsubsuperscriptelement/
---
## IMathLeftSubSuperscriptElement interface

Specifies the Sub-Superscript object, which consists of a base and a subscript and superscript placed to the left of the base.

```csharp
public interface IMathLeftSubSuperscriptElement : IMathElement
```

## Members

| name | description |
| --- | --- |
| [AsIMathElement](asimathelement) { get; } | Allows to get base IMathElement interface [`IMathElement`](../imathelement) |
| [Base](base) { get; } | Base argument |
| [Subscript](subscript) { get; } | Subscript |
| [Superscript](superscript) { get; } | Superscript |

## Examples

Example:

```csharp
[C#]
IMathLeftSubSuperscriptElement leftSubsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheLeft("i", "j");
```

### See Also

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
