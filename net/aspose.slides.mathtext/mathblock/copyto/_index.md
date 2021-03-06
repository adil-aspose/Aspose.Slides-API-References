---
title: CopyTo
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 50
url: /net/aspose.slides.mathtext/mathblock/copyto/
---
## MathBlock.CopyTo method

Copy to specified array.

```csharp
public void CopyTo(IMathElement[] array, int arrayIndex)
```

| parameter | description |
| --- | --- |
| array | Array to copy to. |
| arrayIndex | Index to begin copying. |

## Examples

Example:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
mathBlock.CopyTo(destinationArray, 0);
```

### See Also

* interface [IMathElement](../../imathelement)
* class [MathBlock](../../mathblock)
* namespace [Aspose.Slides.MathText](../../mathblock)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
