---
title: IPortion Class
type: docs
weight: 2170
url: /python/aspose.slides/iportion/
---

Represents a portion of text inside a text paragraph.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.IPortion

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The IPortion type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|portion_format|Returns formatting object which contains explicitly set formatting properties of the text portion with no inheritance applied.<br/>            Read-only [IPortionFormat](/python/aspose.slides/iportionformat/).|
|text|Gets or sets the plain text of a portion.<br/>            Read/write string.|
|field|Returns a field of this portion.<br/>            Read-only [IField](/python/aspose.slides/ifield/).|
|as_islide_component|Allows to get base ISlideComponent interface.<br/>            Read-only [ISlideComponent](/python/aspose.slides/islidecomponent/).|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/python/aspose.slides/ibaseslide/).|
|as_ipresentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/python/aspose.slides/ipresentationcomponent/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/python/aspose.slides/ipresentation/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|add_field(field_type)|Converts this portion to the automaticaly updated field.|
|add_field(internal_string)|Converts this portion to the automaticaly updated field.|
|remove_field()|Converts this field portion to the simple portion.|
|get_rect()|Get coordinates of rect that bounds portion. The rect includes all the lines of<br/>             text in portion, including empty ones.|
|get_coordinates()|Get coordinates of the beginning of the portion. The X coordinate of point represents the <br/>            portion beginning from the first character including left side bearing. The Y coordinate <br/>            includes top side bearing.|
