---
title: RemoveSummaryZoomSection
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 30
url: /net/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection.RemoveSummaryZoomSection method

Remove Summary Zoom Section object from the collection.

```csharp
public void RemoveSummaryZoomSection(ISection section)
```

| parameter | description |
| --- | --- |
| section | Section for which the Summary Zoom Section element is to be removed [`ISection`](../../isection). |

## Examples

The example demonstrates getting Summary Zoom Section element by index:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    collection.RemoveSummaryZoomSection(pres.Sections[1]);
}
```

### See Also

* interface [ISection](../../isection)
* interface [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* namespace [Aspose.Slides](../../isummaryzoomsectioncollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->