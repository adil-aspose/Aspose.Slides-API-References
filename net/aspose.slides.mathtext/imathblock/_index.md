---
title: IMathBlock
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 7670
url: /net/aspose.slides.mathtext/imathblock/
---
## IMathBlock interface

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line. All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

```csharp
public interface IMathBlock : IMathElement, IMathElementCollection
```

## Members

| name | description |
| --- | --- |
| [AsIMathElement](asimathelement) { get; } | Allows to get base IMathElement interface [`IMathElement`](../imathelement) |
| [AsIMathElementCollection](asimathelementcollection) { get; } | Allows to get base IMathElementCollection interface [`IMathElementCollection`](../imathelementcollection) |
| [Delimit](delimit)(…) | Delimits all child elements with separator character (without the brackets) |
| [Enclose](enclose)(…) | Encloses child elements of this block in specified characters such as parenthesis or another as framing and delimit with a separator character |
| [JoinBlock](joinblock)(…) | Joins another mathematical block with this one |
| [WriteAsMathMl](writeasmathml)(…) | Saves content of this [`IMathBlock`](../imathblock) as MathML |

## Examples

Example:

```csharp
[C#]
IMathBlock mathBlock = new MathBlock();
```

### See Also

* interface [IMathElement](../imathelement)
* interface [IMathElementCollection](../imathelementcollection)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
