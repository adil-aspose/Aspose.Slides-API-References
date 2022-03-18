---
title: Add
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection.Add method

Add a specified FallBack rule to the end of the collection.

```csharp
public void Add(IFontFallBackRule sourceRule)
```

| parameter | description |
| --- | --- |
| sourceRule | Specified rule for adding |

## Examples

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
    //Getting of empty or preinitialized rules collection from FontsManager
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    //Adding of new rule to collection
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
}
```

### See Also

* interface [IFontFallBackRule](../../ifontfallbackrule)
* class [FontFallBackRulesCollection](../../fontfallbackrulescollection)
* namespace [Aspose.Slides](../../fontfallbackrulescollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->