---
title: BulletFormat Class
type: docs
weight: 180
url: /python/aspose.slides/bulletformat/
---

Represents paragraph bullet formatting properties.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.BulletFormat

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The BulletFormat type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|as_ipresentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/python/aspose.slides/ipresentationcomponent/).|
|type|Returns or sets the bullet type of a paragraph with no inheritance.<br/>            Read/write [BulletType](/python/aspose.slides/bullettype/).|
|char|Returns or sets the bullet char of a paragraph with no inheritance.<br/>            Read/write char.|
|font|Returns or sets the bullet font of a paragraph with no inheritance.<br/>            Read/write [IFontData](/python/aspose.slides/ifontdata/).|
|height|Returns or sets the bullet height of a paragraph with no inheritance.<br/>            Value float.NaN determines that bullet inherits height from the first portion in the paragraph.<br/>            Read/write|
|color|Returns the color format of a bullet of a paragraph with no inheritance.<br/>            Read-only [IColorFormat](/python/aspose.slides/icolorformat/).|
|numbered_bullet_start_with|Returns or sets the first number which is used for group of numbered bullets with no inheritance.<br/>            Read/write int.|
|numbered_bullet_style|Returns or sets the style of a numbered bullet with no inheritance.<br/>            Read/write [NumberedBulletStyle](/python/aspose.slides/numberedbulletstyle/).|
|is_bullet_hard_color|Determines whether the bullet has own color or inherits it from the first portion in the paragraph.<br/>            NullableBool.True if bullet has own color and NullableBool.False if bullet<br/>            inherits color from the first portion in the paragraph.<br/>            Read/write [NullableBool](/python/aspose.slides/nullablebool/).|
|is_bullet_hard_font|Determines whether the bullet has own font or inherits it from the first portion in the paragraph.<br/>            NullableBool.True if bullet has own font and NullableBool.False if bullet<br/>            inherits font from the first portion in the paragraph.<br/>            Read/write [NullableBool](/python/aspose.slides/nullablebool/).|
|picture|Returns the picture used as a bullet in a paragraph with no inheritance.<br/>            Read-only [ISlidesPicture](/python/aspose.slides/islidespicture/).|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/python/aspose.slides/ibaseslide/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/python/aspose.slides/ipresentation/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|apply_default_paragraph_indents_shifts()|Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values).|
|get_effective()|Gets effective bullet formatting data with the inheritance applied.|
