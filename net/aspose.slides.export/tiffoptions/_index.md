---
title: TiffOptions
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 4390
url: /net/aspose.slides.export/tiffoptions/
---
## TiffOptions class

Provides options that control how a presentation is saved in TIFF format.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Public Members

| name | description |
| --- | --- |
| [TiffOptions](tiffoptions)() | Default constructor. |
| [CompressionType](compressiontype) { get; set; } | Specifies the compression type. Read/write [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DpiX](dpix) { get; set; } | Specifies the horizontal resolution in dots per inch. Read/write UInt32. |
| [DpiY](dpiy) { get; set; } | Specifies the vertical resolution in dots per inch. Read/write UInt32. |
| [ImageSize](imagesize) { get; set; } | Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write Size. |
| [NotesCommentsLayouting](notescommentslayouting) { get; } | Provides options that control how notes and comments is placed in exported document. |
| [PixelFormat](pixelformat) { get; set; } | Specifies the pixel format for the generated images. Read/write [`ImagePixelFormat`](../imagepixelformat). |
| [ShowHiddenSlides](showhiddenslides) { get; set; } | Specifies whether the generated document should include hidden slides or not. Default is `false`. |

### See Also

* class [SaveOptions](../saveoptions)
* interface [ITiffOptions](../itiffoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->