---
title: HtmlOptions
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 3820
url: /net/aspose.slides.export/htmloptions/
---
## HtmlOptions class

Represents a HTML exporting options.

```csharp
public class HtmlOptions : SaveOptions, IHtmlOptions
```

## Public Members

| name | description |
| --- | --- |
| [HtmlOptions](htmloptions)() | Creates a new HtmlOptions object for saving into single HTML file. |
| [HtmlOptions](htmloptions)(…) | Creates a new HtmlOptions object specifiing callback. |
| [DeletePicturesCroppedAreas](deletepicturescroppedareas) { get; set; } | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |
| [HtmlFormatter](htmlformatter) { get; set; } | Returns or sets HTML template. Read/write [`IHtmlFormatter`](../ihtmlformatter). |
| [JpegQuality](jpegquality) { get; set; } | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write Byte. |
| [NotesCommentsLayouting](notescommentslayouting) { get; } | Provides options that control how notes and comments is placed in exported document. |
| [PicturesCompression](picturescompression) { get; set; } | Represents the pictures compression level |
| [ShowHiddenSlides](showhiddenslides) { get; set; } | Specifies whether the generated document should include hidden slides or not. Default is `false`. |
| [SlideImageFormat](slideimageformat) { get; set; } | Returns or sets slide image format options. Read/write [`ISlideImageFormat`](../islideimageformat). |
| [SvgResponsiveLayout](svgresponsivelayout) { get; set; } | True to exclude width and height attributes from svg container - that will make layout responsive. False - otherwise. Read/write Boolean. |

### See Also

* class [SaveOptions](../saveoptions)
* interface [IHtmlOptions](../ihtmloptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
