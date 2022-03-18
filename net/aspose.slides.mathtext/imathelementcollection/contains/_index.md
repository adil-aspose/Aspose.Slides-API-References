---
title: Contains
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 50
url: /net/aspose.slides.mathtext/imathelementcollection/contains/
---
## IMathElementCollection.Contains method

Determines whether the collection contains a specific value.

```csharp
public bool Contains(IMathElement item)
```

| parameter | description |
| --- | --- |
| item | The object to locate in the collection. |

## Return Value

true if *item* is found in the collection; otherwise, false.

## Examples

Example:

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
collection.Add(plusElement);
collection.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
bool contains = collection.Contains(plusElement);
```

### See Also

* interface [IMathElement](../../imathelement)
* interface [IMathElementCollection](../../imathelementcollection)
* namespace [Aspose.Slides.MathText](../../imathelementcollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->