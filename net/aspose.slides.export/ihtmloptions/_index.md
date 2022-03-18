---
title: IHtmlOptions
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 3900
url: /net/aspose.slides.export/ihtmloptions/
---
## IHtmlOptions interface

Represents a HTML exporting options.

```csharp
public interface IHtmlOptions : ISaveOptions
```

## Members

| name | description |
| --- | --- |
| [AsISaveOptions](asisaveoptions) { get; } | Returns ISaveOptions interface. Read-only [`ISaveOptions`](../isaveoptions). |
| [DeletePicturesCroppedAreas](deletepicturescroppedareas) { get; set; } | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) Read/write Boolean. |
| [HtmlFormatter](htmlformatter) { get; set; } | Returns or sets HTML template. Read/write [`IHtmlFormatter`](../ihtmlformatter). |
| [JpegQuality](jpegquality) { get; set; } | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write Byte. |
| [NotesCommentsLayouting](notescommentslayouting) { get; } | Provides options that control how notes and comments is placed in exported document. |
| [PicturesCompression](picturescompression) { get; set; } | Represents the pictures compression level Read/write [`PicturesCompression`](./picturescompression). |
| [ShowHiddenSlides](showhiddenslides) { get; set; } | Specifies whether the generated document should include hidden slides or not. Default is `false`. |
| [SlideImageFormat](slideimageformat) { get; set; } | Returns or sets slide image format options. Read/write [`ISlideImageFormat`](../islideimageformat). |
| [SvgResponsiveLayout](svgresponsivelayout) { get; set; } | True to exclude width and height attributes from SVG container - that will make layout responsive. False - otherwise. Read/write Boolean. |

### See Also

* interface [ISaveOptions](../isaveoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->