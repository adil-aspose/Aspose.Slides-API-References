---
title: Insert
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 20
url: /net/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection.Insert method

Inserts IMathBlock into the collection at the specified index.

```csharp
public void Insert(int index, IMathBlock item)
```

| parameter | description |
| --- | --- |
| index | The zero-based index at which an item should be inserted. |
| item | The IMathBlock to insert. |

## Examples

Example:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Insert(0, block);
```

### See Also

* interface [IMathBlock](../../imathblock)
* interface [IMathBlockCollection](../../imathblockcollection)
* namespace [Aspose.Slides.MathText](../../imathblockcollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
