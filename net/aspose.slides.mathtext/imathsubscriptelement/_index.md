---
title: IMathSubscriptElement
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 7990
url: /net/aspose.slides.mathtext/imathsubscriptelement/
---
## IMathSubscriptElement interface

Specifies the subscript object, which consists of a base and a reduced-size subscript placed below and to the right.

```csharp
public interface IMathSubscriptElement : IMathElement
```

## Members

| name | description |
| --- | --- |
| [AsIMathElement](asimathelement) { get; } | Allows to get base IMathElement interface [`IMathElement`](../imathelement) |
| [Base](base) { get; } | Base argument |
| [Subscript](subscript) { get; } | Subscript |

## Examples

Example:

```csharp
[C#]
IMathSubscriptElement subscriptElement = new MathematicalText("N").SetSubscript("i");
```

### See Also

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->