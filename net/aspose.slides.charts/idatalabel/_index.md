---
title: IDataLabel
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 1900
url: /net/aspose.slides.charts/idatalabel/
---
## IDataLabel interface

Represents a series labels.

```csharp
public interface IDataLabel : IActualLayout, ILayoutable, IOverridableText
```

## Members

| name | description |
| --- | --- |
| [AsIActualLayout](asiactuallayout) { get; } | Returns IActualLayout interface. |
| [AsILayoutable](asilayoutable) { get; } | Returns ILayoutable interface. Read-only [`ILayoutable`](../ilayoutable). |
| [AsIOverridableText](asioverridabletext) { get; } | Returns IOverridableText interface. Read-only [`IOverridableText`](../ioverridabletext). |
| [DataLabelFormat](datalabelformat) { get; } | Returns format of the data label. Read-only [`IDataLabelFormat`](../idatalabelformat). |
| [IsVisible](isvisible) { get; } | False means that data label is not visible (and so all Show*-flags (ShowValue, ...) are false). Read-only Boolean. |
| [ValueFromCell](valuefromcell) { get; set; } | Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true. |
| [GetActualLabelText](getactuallabeltext)() | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |
| [Hide](hide)() | Make data label hidden by setting all Show*-flags (ShowValue, ...) to false state. IsVisible will be false after this. |

### See Also

* interface [IActualLayout](../iactuallayout)
* interface [ILayoutable](../ilayoutable)
* interface [IOverridableText](../ioverridabletext)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
