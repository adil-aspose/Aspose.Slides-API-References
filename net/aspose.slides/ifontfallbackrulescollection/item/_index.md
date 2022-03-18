---
title: Item
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 30
url: /net/aspose.slides/ifontfallbackrulescollection/item/
---
## IFontFallBackRulesCollection indexer

Gets the rule at the specified index. Read-only [`IFontFallBackRule`](../../ifontfallbackrule).

```csharp
public IFontFallBackRule this[int index] { get; }
```

## Examples

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
    //Getting of empty or preinitialized rules collection from FontsManager
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    //Adding of several rules to collection
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
    rulesList.Add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));

    //Retrieving of object of the first rule in collection
    IFontFallBackRule firstRule = rulesList[0];
}
```

### See Also

* interface [IFontFallBackRule](../../ifontfallbackrule)
* interface [IFontFallBackRulesCollection](../../ifontfallbackrulescollection)
* namespace [Aspose.Slides](../../ifontfallbackrulescollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->