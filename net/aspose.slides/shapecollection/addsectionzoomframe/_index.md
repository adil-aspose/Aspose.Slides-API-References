---
title: AddSectionZoomFrame
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 110
url: /net/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection.AddSectionZoomFrame method (1 of 2)

Adds a new Section Zoom object to the end of a collection.

```csharp
public ISectionZoomFrame AddSectionZoomFrame(float x, float y, float width, float height, 
    ISection section)
```

| parameter | description |
| --- | --- |
| x | X coordinate of a new Section Zoom frame Single. |
| y | Y coordinate of a new Section Zoom frame Single. |
| width | Width of a new Section Zoom frame Single. |
| height | Height of a new Section Zoom frame Single. |
| section | The section object referenced by the Section Zoom frame [`ISection`](../../isection). |

## Return Value

Created Section Zoom object [`ISectionZoomFrame`](../../isectionzoomframe).

## Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |

## Examples

This example demonstrates adding a Section Zoom object to the end of a collection (assume that there are at least two sections in the "Presentation.pptx" presentation):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    ISectionZoomFrame zoomFrame = pres.Slides[0].Shapes.AddSectionZoomFrame(150, 20, 50, 50, pres.Sections[1]);
}
```

### See Also

* interface [ISectionZoomFrame](../../isectionzoomframe)
* interface [ISection](../../isection)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## ShapeCollection.AddSectionZoomFrame method (2 of 2)

Adds a new Section Zoom object to the end of a collection with a predefined image.

```csharp
public ISectionZoomFrame AddSectionZoomFrame(float x, float y, float width, float height, 
    ISection section, IPPImage image)
```

| parameter | description |
| --- | --- |
| x | X coordinate of a new Section Zoom frame Single. |
| y | Y coordinate of a new Section Zoom frame Single. |
| width | Width of a new Section Zoom frame Single. |
| height | Height of a new Section Zoom frame Single. |
| section | The section object referenced by the Section Zoom frame [`ISection`](../../isection). |
| image | The image for the referenced slide [`IPPImage`](../../ippimage) |

## Return Value

Created Section Zoom object [`ISectionZoomFrame`](../../isectionzoomframe).

## Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |

## Examples

This example demonstrates adding a Section Zoom object to the end of a collection (assume that there are at least two sections in the "Presentation.pptx" presentation):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    ISectionZoomFrame zoomFrame = pres.Slides[0].Shapes.AddSectionZoomFrame(150, 20, 50, 50, pres.Sections[1], image);
}
```

### See Also

* interface [ISectionZoomFrame](../../isectionzoomframe)
* interface [ISection](../../isection)
* interface [IPPImage](../../ippimage)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
