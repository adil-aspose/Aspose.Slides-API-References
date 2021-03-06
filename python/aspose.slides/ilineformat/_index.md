---
title: ILineFormat Class
type: docs
weight: 1780
url: /python/aspose.slides/ilineformat/
---

Represents format of a line.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.ILineFormat

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The ILineFormat type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|is_format_not_defined|Returns true if line format is not defined (as just created, default).<br/>            Read-only bool.|
|fill_format|Returns the fill format of a line.<br/>            Read-only [ILineFillFormat](/python/aspose.slides/ilinefillformat/).|
|sketch_format|Returns the sketch format of a line.<br/>            Read-only [ISketchFormat](/python/aspose.slides/isketchformat/).|
|width|Returns or sets the width of a line.<br/>            Read/write float.|
|dash_style|Returns or sets the line dash style.<br/>            Read/write [LineDashStyle](/python/aspose.slides/linedashstyle/).|
|custom_dash_pattern|Returns or sets the custom dash pattern.<br/>            Read/write|
|cap_style|Returns or sets the line cap style.<br/>            Read/write [LineCapStyle](/python/aspose.slides/linecapstyle/).|
|style|Returns or sets the line style.<br/>            Read/write [LineStyle](/python/aspose.slides/linestyle/).|
|alignment|Returns or sets the line alignment.<br/>            Read/write [LineAlignment](/python/aspose.slides/linealignment/).|
|join_style|Returns or sets the lines join style.<br/>            Read/write [LineJoinStyle](/python/aspose.slides/linejoinstyle/).|
|miter_limit|Returns or sets the miter limit of a line.<br/>            Read/write|
|begin_arrowhead_style|Returns or sets the arrowhead style at the beginning of a line.<br/>            Read/write [LineArrowheadStyle](/python/aspose.slides/linearrowheadstyle/).|
|end_arrowhead_style|Returns or sets the arrowhead style at the end of a line.<br/>            Read/write [LineArrowheadStyle](/python/aspose.slides/linearrowheadstyle/).|
|begin_arrowhead_width|Returns or sets the arrowhead width at the beginning of a line.<br/>            Read/write [LineArrowheadWidth](/python/aspose.slides/linearrowheadwidth/).|
|end_arrowhead_width|Returns or sets the arrowhead width at the end of a line.<br/>            Read/write [LineArrowheadWidth](/python/aspose.slides/linearrowheadwidth/).|
|begin_arrowhead_length|Returns or sets the arrowhead length at the beginning of a line.<br/>            Read/write [LineArrowheadLength](/python/aspose.slides/linearrowheadlength/).|
|end_arrowhead_length|Returns or sets the arrowhead length at the end of a line.<br/>            Read/write [LineArrowheadLength](/python/aspose.slides/linearrowheadlength/).|
|as_iline_param_source|Allows to get base ILineParamSource interface.<br/>            Read-only [ILineParamSource](/python/aspose.slides/ilineparamsource/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|equals(line_format)|Determines whether the two LineFormat instances are equal.|
|get_effective()|Gets effective line formatting data with the inheritance applied.|
