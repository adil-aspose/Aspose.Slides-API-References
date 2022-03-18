---
title: Remove
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 30
url: /net/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule.Remove method

Removes the first occurrence of a specific FallBack font from the list.

```csharp
public void Remove(string fontName)
```

| parameter | description |
| --- | --- |
| fontName | The font's name to remove from the list. |

## Examples

```csharp
[C#]
// Create a rule contains a list of fonts.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

// Remove Tahoma from the list.
newRule.Remove ("Tahoma");
```

### See Also

* class [FontFallBackRule](../../fontfallbackrule)
* namespace [Aspose.Slides](../../fontfallbackrule)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->