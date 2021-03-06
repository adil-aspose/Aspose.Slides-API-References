---
title: IChartTitle Class
type: docs
weight: 710
url: /python/aspose.slides.charts/icharttitle/
---

Represents chart title properties.

**Namespace:** [aspose.slides.charts](/python/aspose.slides.charts/)

**Full Class Name:** aspose.slides.charts.IChartTitle

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The IChartTitle type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|overlay|Determines whether other chart elements shall be allowed to overlap title.<br/>            Read/write bool.|
|format|Returns the fill, line, effect styles of a title.<br/>            Read-only [IFormat](/python/aspose.slides.charts/iformat/).|
|as_ilayoutable|Allows to get base ILayoutable interface.<br/>            Read-only [ILayoutable](/python/aspose.slides.charts/ilayoutable/).|
|as_ioverridable_text|Allows to get base IOverridableText interface.<br/>            Read-only [IOverridableText](/python/aspose.slides.charts/ioverridabletext/).|
|x|Specifies the x location (left) of the chart element as a fraction of the width of the chart.<br/>            Read/write|
|y|Specifies the top of the chart element as a fraction of the height of the chart.<br/>            Read/write|
|width|Specifies the width of the chart element as a fraction of the width of the chart.<br/>            Read/write|
|height|Specifies the height of the chart element as a fraction of the height of the chart.<br/>            Read/write|
|right|Gets the right of the chart element as a fraction of the width of the chart.<br/>            Read-only|
|bottom|Gets the top of the chart element as a fraction of the height of the chart.<br/>            Read-only|
|chart|Returns the chart.<br/>            Read-only [IChart](/python/aspose.slides.charts/ichart/).|
|as_islide_component|Allows to get base ISlideComponent interface.<br/>            Read-only [ISlideComponent](/python/aspose.slides/islidecomponent/).|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/python/aspose.slides/ibaseslide/).|
|as_ipresentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/python/aspose.slides/ipresentationcomponent/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/python/aspose.slides/ipresentation/).|
|text_frame_for_overriding|Can contain a rich formatted text. If this property is not null then this <br/>            formatted text value overrides auto-generated text.<br/>            Auto-generated text is an implicit property of the data label, the display <br/>            unit label of the value axis, the axis title, the chart title, the label of the trendline.<br/>            Auto-generated text is formatted with the IFormattedTextContainer.TextFormat property.<br/>            Read-only [ITextFrame](/python/aspose.slides/itextframe/).|
|as_iformatted_text_container|Allows to get base IFormattedTextContainer interface.<br/>            Read-only [IFormattedTextContainer](/python/aspose.slides.charts/iformattedtextcontainer/).|
|text_format|Returns chart text format.<br/>            Read-only [IChartTextFormat](/python/aspose.slides.charts/icharttextformat/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|add_text_frame_for_overriding(text)|Initialize TextFrameForOverriding with the text in paramener "text".<br/>            If TextFrameForOverriding is already initialized then simply changes its text.|
