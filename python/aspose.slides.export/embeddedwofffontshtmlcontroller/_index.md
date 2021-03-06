---
title: EmbeddedWoffFontsHtmlController Class
type: docs
weight: 30
url: /python/aspose.slides.export/embeddedwofffontshtmlcontroller/
---

The formatting controller class to use for fonts embedding in WOFF format

**Namespace:** [aspose.slides.export](/python/aspose.slides.export/)

**Full Class Name:** aspose.slides.export.EmbeddedWoffFontsHtmlController

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The EmbeddedWoffFontsHtmlController type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmbeddedWoffFontsHtmlController()|Creates new instance.|
|EmbeddedWoffFontsHtmlController(controller)|Initializes a new instance of the EmbeddedWoffFontsHtmlController class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|as_ihtml_formatting_controller|Returns IHtmlFormattingController interface.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|write_document_start(generator, presentation)|Called to write html document header. Called once per presentation conversion.|
|write_document_end(generator, presentation)|Called to write html document footer. Called once per presentation conversion.|
|write_slide_start(generator, slide)|Called to write html slide header. Called once per each of slides.|
|write_slide_end(generator, slide)|Called to write html slide footer. Called once per each of slides.|
|write_shape_start(generator, shape)|Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous.|
|write_shape_end(generator, shape)|Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous.|
