---
title: IViewProperties
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 7060
url: /net/aspose.slides/iviewproperties/
---
## IViewProperties interface

Presentation wide view properties.

```csharp
public interface IViewProperties
```

## Members

| name | description |
| --- | --- |
| [LastView](lastview) { get; set; } | Specifies the view mode that was used when the presentation document was last saved. Read/write [`ViewType`](../viewtype). |
| [NormalViewProperties](normalviewproperties) { get; } | Represents normal view properties. The normal view consists of three content regions: the slide itself, a side content region, and a bottom content region. Read-only [`INormalViewProperties`](../inormalviewproperties). |
| [NotesViewProperties](notesviewproperties) { get; } | Specifies common view properties associated with the notes view mode. Read-only [`ICommonSlideViewProperties`](../icommonslideviewproperties). |
| [ShowComments](showcomments) { get; set; } | Specifies whether the slide comments should be shown. Read/write [`NullableBool`](../nullablebool). |
| [SlideViewProperties](slideviewproperties) { get; } | Specifies common view properties associated with the slide view mode. Read-only [`ICommonSlideViewProperties`](../icommonslideviewproperties). |

### See Also

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
