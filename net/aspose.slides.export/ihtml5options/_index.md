---
title: IHtml5Options
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 3860
url: /net/aspose.slides.export/ihtml5options/
---
## IHtml5Options interface

Represents a HTML5 exporting options.

```csharp
public interface IHtml5Options : ISaveOptions
```

## Members

| name | description |
| --- | --- |
| [AnimateShapes](animateshapes) { get; set; } | Returns or sets shapes animation option. Read/write Boolean. |
| [AnimateTransitions](animatetransitions) { get; set; } | Returns or sets transitions animation option. Read/write Boolean. |
| [AsISaveOptions](asisaveoptions) { get; } | Returns ISaveOptions interface. Read-only [`ISaveOptions`](../isaveoptions). |

## Examples

Example:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, new Html5Options()
  {
      AnimateShapes = true,
      AnimateTransitions = true
  });
}
```

### See Also

* interface [ISaveOptions](../isaveoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->