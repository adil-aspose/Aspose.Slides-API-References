---
title: InsertSectionZoomFrame
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 90
url: /net/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection.InsertSectionZoomFrame method (1 of 2)

Creates a new Section Zoom object and inserts into to a collection at the specified index.

```csharp
public ISectionZoomFrame InsertSectionZoomFrame(int index, float x, float y, float width, 
    float height, ISection section)
```

| parameter | description |
| --- | --- |
| index | The zero-based index at which Section Zoom frame should be inserted. |
| x | X coordinate of a new Section Zoom frame Single. |
| y | Y coordinate of a new Section Zoom frame Single. |
| width | Width of a new Section Zoom frame Single. |
| height | Height of a new Section Zoom frame Single. |
| section | The slide object referenced by the Section Zoom frame [`ISection`](../../isection). |

## Return Value

Created Section Zoom object [`ISectionZoomFrame`](../../isectionzoomframe).

## Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |

## Examples

This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection (assume that there are at least two sections in the "Presentation.pptx" presentation):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    ISectionZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertSectionZoomFrame(2, 150, 20, 50, 50, pres.Sections[1]);
}
```

### See Also

* interface [ISectionZoomFrame](../../isectionzoomframe)
* interface [ISection](../../isection)
* interface [IShapeCollection](../../ishapecollection)
* namespace [Aspose.Slides](../../ishapecollection)
* assembly [Aspose.Slides](../../../)

---

## IShapeCollection.InsertSectionZoomFrame method (2 of 2)

Creates a new Section Zoom object and inserts it to a collection at the specified index.

```csharp
public ISectionZoomFrame InsertSectionZoomFrame(int index, float x, float y, float width, 
    float height, ISection section, IPPImage image)
```

| parameter | description |
| --- | --- |
| index | The zero-based index at which Section Zoom frame should be inserted. |
| x | X coordinate of a new Section Zoom frame Single. |
| y | Y coordinate of a new Section Zoom frame Single. |
| width | Width of a new Section Zoom frame Single. |
| height | Height of a new Section Zoom frame Single. |
| section | The slide object referenced by the Section Zoom frame [`ISection`](../../isection). |
| image | The image for the referenced slide [`IPPImage`](../../ippimage) |

## Return Value

Created Section Zoom object [`ISectionZoomFrame`](../../isectionzoomframe).

## Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |

## Examples

This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection (assume that there are at least two sections in the "Presentation.pptx" presentation):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    ISectionZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertSectionZoomFrame(2, 150, 20, 50, 50, pres.Sections[1], image);
}
```

### See Also

* interface [ISectionZoomFrame](../../isectionzoomframe)
* interface [ISection](../../isection)
* interface [IPPImage](../../ippimage)
* interface [IShapeCollection](../../ishapecollection)
* namespace [Aspose.Slides](../../ishapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
