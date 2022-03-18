---
title: ILayoutSlide
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 5910
url: /net/aspose.slides/ilayoutslide/
---
## ILayoutSlide interface

Represents a layout slide.

```csharp
public interface ILayoutSlide : IBaseSlide, IOverrideThemeable
```

## Members

| name | description |
| --- | --- |
| [AsIBaseSlide](asibaseslide) { get; } | Allows to get base IBaseSlide interface. Read-only [`IBaseSlide`](../ibaseslide). |
| [AsIOverrideThemeable](asioverridethemeable) { get; } | Returns IOverrideThemeable interface. Read-only [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [HasDependingSlides](hasdependingslides) { get; } | Returns true if there exists at least one slide that depends on this layout slide. Read-only Boolean. |
| [HeaderFooterManager](headerfootermanager) { get; } | Returns HeaderFooter manager of the layout slide. Read-only [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [LayoutType](layouttype) { get; } | Returns layout type of this layout slide. Read-only [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](masterslide) { get; set; } | Returns or sets the master slide for a layout. Read/write [`IMasterSlide`](../imasterslide). |
| [GetDependingSlides](getdependingslides)() | Returns an array with all slides, which depend on this layout slide. |
| [Remove](remove)() | Removes layout from presentation. |

### See Also

* interface [IBaseSlide](../ibaseslide)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->