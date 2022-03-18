---
title: MathRightSubSuperscriptElement
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 8470
url: /net/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement class

Specifies the Sub-Superscript object, which consists of a base and a subscript and superscript placed to the right of the base.

```csharp
public sealed class MathRightSubSuperscriptElement : BaseScript, IMathRightSubSuperscriptElement
```

## Public Members

| name | description |
| --- | --- |
| [MathRightSubSuperscriptElement](mathrightsubsuperscriptelement)(…) | Initializes a new instance of the MathRightSubSuperscriptElement class. |
| [AlignScripts](alignscripts) { get; set; } | Specifies the alignment of subscript/superscript. When true, subscript and superscript are aligned horizontally to each other. When false, they are kerned to the shape of the base. Default value is false. |
| [Subscript](subscript) { get; } | Subscript argument |
| [Superscript](superscript) { get; } | Superscript argument |
| [GetChildren](getchildren)() | Get children elements |

## Examples

Example:

```csharp
[C#]
MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```

### See Also

* class [BaseScript](../basescript)
* interface [IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->