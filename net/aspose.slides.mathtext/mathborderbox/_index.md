---
title: MathBorderBox
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 8130
url: /net/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox class

Draws a rectangular or some other border around the IMathElement.

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## Public Members

| name | description |
| --- | --- |
| [MathBorderBox](mathborderbox)(…) | Creates MathBorderBox element with rectangular border (2 constructors) |
| [Base](base) { get; } | Base argument |
| [HideBottom](hidebottom) { get; set; } | Hide Bottom Edge (default is false) - specifies the hidden or shown state of the bottom edge of border box. |
| [HideLeft](hideleft) { get; set; } | Hide Left Edge (default is false) - specifies the hidden or shown state of the left edge of border box. |
| [HideRight](hideright) { get; set; } | Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box. |
| [HideTop](hidetop) { get; set; } | Hide Top Edge (default is false) - specifies the hidden or shown state of the top edge of border box. |
| [StrikethroughBottomLeftToTopRight](strikethroughbottomlefttotopright) { get; set; } | Strikethrough Bottom-Left to Top-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the bottom-left corner to the top-right corner of border box. |
| [StrikethroughHorizontal](strikethroughhorizontal) { get; set; } | Strikethrough Horizontal (default is false) - specifies the hidden or shown state of a strikethrough horizontal line. |
| [StrikethroughTopLeftToBottomRight](strikethroughtoplefttobottomright) { get; set; } | Strikethrough Top-Left to Bottom-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the top-left corner to the bottom-right corner of border box. |
| [StrikethroughVertical](strikethroughvertical) { get; set; } | Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line. |
| [GetChildren](getchildren)() | Get children elements |

## Examples

Example:

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### See Also

* class [MathElementBase](../mathelementbase)
* interface [IMathBorderBox](../imathborderbox)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
