---
title: LayoutSlide
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 7190
url: /net/aspose.slides/layoutslide/
---
## LayoutSlide class

Represents a layout slide.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Public Members

| name | description |
| --- | --- |
| [HasDependingSlides](hasdependingslides) { get; } | Returns true if there exists at least one slide that depends on this layout slide. Read-only Boolean. |
| [HeaderFooterManager](headerfootermanager) { get; } | Returns HeaderFooter manager of the layout slide. Read-only [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [LayoutType](layouttype) { get; } | Returns layout type of this layout slide. Read-only [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](masterslide) { get; set; } | Returns or sets the master slide for a layout. Read/write [`IMasterSlide`](../imasterslide). |
| override [ShowMasterShapes](showmastershapes) { get; set; } | Specifies if shapes on the master slide should be shown on slides or not. Read/write Boolean. |
| [ThemeManager](thememanager) { get; } | Returns the overriding theme manager. Read-only [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [GetDependingSlides](getdependingslides)() | Returns an array with all slides, which depend on this layout slide. |
| [Remove](remove)() | Removes layout from presentation. |

### See Also

* class [BaseSlide](../baseslide)
* interface [ILayoutSlide](../ilayoutslide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->