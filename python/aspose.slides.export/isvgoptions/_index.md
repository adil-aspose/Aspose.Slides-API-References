---
title: ISVGOptions Class
type: docs
weight: 240
url: /python/aspose.slides.export/isvgoptions/
---

Represents an SVG options.

**Namespace:** [aspose.slides.export](/python/aspose.slides.export/)

**Full Class Name:** aspose.slides.export.ISVGOptions

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The ISVGOptions type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|vectorize_text|Determines whether the text on a slide will be saved as graphics.<br/>            Read/write bool.|
|metafile_rasterization_dpi|Returns or sets the lower resolution limit for metafile rasterization.<br/>            Read/write|
|disable3_dtext|Determines whether the 3D text is disabled in SVG.<br/>            Read/write bool.|
|disable_gradient_split|Disables splitting FromCornerX and FromCenter gradients.<br/>            Read/write bool.|
|disable_line_end_cropping|SVG 1.1 lacks ability to define insets for markers.<br/>            Aspose.Slides SVG writing engine has workaround for that problem:<br/>            it crops end of line with arrow, so, line doesn't overlap markers.<br/>            This option switches off such behavior.<br/>            Read/write bool.|
|jpeg_quality|Determines JPEG encoding quality.<br/>            Read/write|
|shape_formatting_controller|Returns and sets a callback interface which allows user to control shape conversion.<br/>            Read/write [ISvgShapeFormattingController](/python/aspose.slides.export/isvgshapeformattingcontroller/).|
|pictures_compression|Represents the pictures compression level<br/>            Read/write [pictures_compression](/python/aspose.slides.export/isvgoptions/).|
|delete_pictures_cropped_areas|A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped <br/>            parts will removed, if false they will be serialized in the document (which can possible lead to a <br/>            larger file)<br/>            Read/write bool.|
|external_fonts_handling|Determines a way of handling externally loaded fonts.<br/>            Read/write [SvgExternalFontsHandling](/python/aspose.slides.export/svgexternalfontshandling/).|
|as_isave_options|Returns ISaveOptions interface.<br/>            Read-only [ISaveOptions](/python/aspose.slides.export/isaveoptions/).|
|warning_callback|Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write [IWarningCallback](/python/aspose.slides.warnings/iwarningcallback/).|
|progress_callback|Represents a callback object for saving progress updates in percentage. <br/>            See [IProgressCallback](/python/aspose.slides/iprogresscallback/).|
|default_regular_font|Returns or sets font used in case source font is not found.<br/>            Read-write string.|
