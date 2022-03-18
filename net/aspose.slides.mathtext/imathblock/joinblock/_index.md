---
title: JoinBlock
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 30
url: /net/aspose.slides.mathtext/imathblock/joinblock/
---
## IMathBlock.JoinBlock method

Joins another mathematical block with this one

```csharp
public IMathBlock JoinBlock(IMathBlock other)
```

| parameter | description |
| --- | --- |
| other | The joining block |

## Return Value

this mathematical block after joining

## Examples

Example:

```csharp
[C#]
IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).Join(new MathematicalText("="));
IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).Join(new MathematicalText("+"))
.Join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
IMathBlock block3 = block1.JoinBlock(block2);
```

### See Also

* interface [IMathBlock](../../imathblock)
* namespace [Aspose.Slides.MathText](../../imathblock)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->