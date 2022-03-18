---
title: Insert
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 80
url: /net/aspose.slides.mathtext/mathblock/insert/
---
## MathBlock.Insert method

Inserts a MathElement into the collection at the specified index.

```csharp
public void Insert(int index, IMathElement item)
```

| parameter | description |
| --- | --- |
| index | The zero-based index at which MathElement should be inserted. |
| item | The MathElement to insert. |

## Examples

Example:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

### See Also

* interface [IMathElement](../../imathelement)
* class [MathBlock](../../mathblock)
* namespace [Aspose.Slides.MathText](../../mathblock)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->