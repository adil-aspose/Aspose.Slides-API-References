---
title: IFontsManager Class
type: docs
weight: 1450
url: /python/aspose.slides/ifontsmanager/
---

Manages fonts across the presentation.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.IFontsManager

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The IFontsManager type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|font_subst_rule_list|Font substitutions to use when rendering<br/>            Read/write [IFontSubstRuleCollection](/python/aspose.slides/ifontsubstrulecollection/).|
|font_fall_back_rules_collection|Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality<br/>            Read/write [IFontFallBackRulesCollection](/python/aspose.slides/ifontfallbackrulescollection/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|add_embedded_font(font_data, embed_font_rule)|Adds the embedded font.|
|add_embedded_font(font_data, embed_font_rule)|Adds the embedded font|
|replace_font(source_font, dest_font)|Replace font in presentation|
|replace_font(subst_rule)|Replace font in presentation using information provided in|
|replace_font(subst_rules)|Replace font in presentation using information provided in collection of|
|get_fonts()|Returns the fonts used in the presentation|
|get_embedded_fonts()|Returns the fonts embedded in the presentation|
|remove_embedded_font(font_data)|Removes the embedded font|
