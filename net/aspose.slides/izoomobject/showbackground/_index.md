---
title: ShowBackground
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 30
url: /net/aspose.slides/izoomobject/showbackground/
---
## IZoomObject.ShowBackground property

Gets or sets value that specifies whether the Zoom will use the background of the destination slide. Read/write Boolean. Default value: true

```csharp
public bool ShowBackground { get; set; }
```

## Examples

The example demonstrates removing the background of an image of a Zoom object:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
    zoomFrame.ShowBackground = false;
}
```

### See Also

* interface [IZoomObject](../../izoomobject)
* namespace [Aspose.Slides](../../izoomobject)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->