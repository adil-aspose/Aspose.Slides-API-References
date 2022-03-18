---
title: MathDelimiter
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 40
url: /net/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter constructor

Initializes MathDelimiter with the specified element as single base argument

```csharp
public MathDelimiter(IMathElement element)
```

| parameter | description |
| --- | --- |
| element | The base element to which the delimiter is applied. Can be null. |

## Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Throws then *element* is a container for another elements, such as MathBlock. In this case, you need to call a different constructor with IEnumerable argument. |

## Examples

Example:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### See Also

* interface [IMathElement](../../imathelement)
* class [MathDelimiter](../../mathdelimiter)
* namespace [Aspose.Slides.MathText](../../mathdelimiter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->