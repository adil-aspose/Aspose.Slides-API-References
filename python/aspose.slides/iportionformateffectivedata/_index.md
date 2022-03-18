---
title: IPortionFormatEffectiveData Class
type: docs
weight: 2210
url: /python/aspose.slides/iportionformateffectivedata/
---

Immutable object which contains effective text portion formatting properties.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.IPortionFormatEffectiveData

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The IPortionFormatEffectiveData type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|bookmark_id|Returns bookmark identifier.<br/>            Read-only string.|
|hyperlink_click|Returns the hyperlink defined for mouse click.<br/>            Read-only [IHyperlink](/python/aspose.slides/ihyperlink/).|
|hyperlink_mouse_over|Returns the hyperlink defined for mouse over.<br/>            Read-only [IHyperlink](/python/aspose.slides/ihyperlink/).|
|as_ibase_portion_format_effective_data|Returns IBasePortionFormatEffectiveData interface.|
|line_format|Returns the LineFormat properties for text outlining.<br/>            Read-only [ILineFormatEffectiveData](/python/aspose.slides/ilineformateffectivedata/).|
|fill_format|Returns the text FillFormat properties.<br/>            Read-only [IFillFormatEffectiveData](/python/aspose.slides/ifillformateffectivedata/).|
|effect_format|Returns the text EffectFormat properties.<br/>            Read-only [IEffectFormatEffectiveData](/python/aspose.slides/ieffectformateffectivedata/).|
|highlight_color|Returns the color used to highlight a text.<br/>            Read-only aspose.pydrawing.Color.|
|underline_line_format|Returns the LineFormat properties used to outline underline line.<br/>            Read-only [ILineFormatEffectiveData](/python/aspose.slides/ilineformateffectivedata/).|
|underline_fill_format|Returns the underline line FillFormat properties.<br/>            Read-only [IFillFormatEffectiveData](/python/aspose.slides/ifillformateffectivedata/).|
|font_bold|Determines whether the font is bold.<br/>            Read-only bool.|
|font_italic|Determines whether the font is itallic.<br/>            Read-only bool.|
|kumimoji|Determines whether the numbers should ignore text eastern language-specific vertical text layout.<br/>            Read-only bool.|
|normalise_height|Determines whether the height of a text should be normalized.<br/>            Read-only bool.|
|proof_disabled|Determines whether the text shouldn't be proofed.<br/>            Read-only bool.|
|font_underline|Returns the text underline type.<br/>            Read-only [TextUnderlineType](/python/aspose.slides/textunderlinetype/).|
|text_cap_type|Returns the type of text capitalization.<br/>            Read-only [TextCapType](/python/aspose.slides/textcaptype/).|
|strikethrough_type|Returns the strikethrough type of a text.<br/>            Read-only [TextStrikethroughType](/python/aspose.slides/textstrikethroughtype/).|
|smart_tag_clean|Determines whether the smart tag should be cleaned.<br/>            Read-only bool.|
|is_hard_underline_line|Determines whether the underline style has own LineFormat properties or inherits it<br/>            from the LineFormat properties of the text.<br/>            Read-only bool.|
|is_hard_underline_fill|Determines whether the underline style has own FillFormat properties or inherits it<br/>            from the FillFormat properties of the text.<br/>            Read-only bool.|
|font_height|Returns the font height of a portion.<br/>            Read-only|
|latin_font|Returns the Latin font info.<br/>            Read-only [IFontData](/python/aspose.slides/ifontdata/).|
|east_asian_font|Returns the East Asian font info.<br/>            Read-only [IFontData](/python/aspose.slides/ifontdata/).|
|complex_script_font|Returns the complex script font info.<br/>            Read-only [IFontData](/python/aspose.slides/ifontdata/).|
|symbol_font|Returns the symbolic font info.<br/>            Read-only [IFontData](/python/aspose.slides/ifontdata/).|
|escapement|Returns the superscript or subscript text.<br/>            Value from -100% (subscript) to 100% (superscript).<br/>            Read-only|
|kerning_minimal_size|Returns the minimal font size, for which kerning should be switched on.<br/>            Read-only|
|language_id|Returns the Id of a language.<br/>            Read-only string.|
|alternative_language_id|Returns the Id of an alternative language.<br/>            Read-only string.|
|spacing|Returns the intercharacter spacing increment.<br/>            Read-only|