---
title: SeparatorCharacter
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 70
url: /net/aspose.slides.mathtext/mathdelimiter/separatorcharacter/
---
## MathDelimiter.SeparatorCharacter property

Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '&#x7C;'.

```csharp
public char SeparatorCharacter { get; set; }
```

## Examples

Example:

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Join("y").Enclose();
delimiter.SeparatorCharacter = '$';
```

### See Also

* class [MathDelimiter](../../mathdelimiter)
* namespace [Aspose.Slides.MathText](../../mathdelimiter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->