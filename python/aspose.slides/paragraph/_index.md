---
title: Paragraph Class
type: docs
weight: 3250
url: /python/aspose.slides/paragraph/
---

Represents a paragraph of text.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.Paragraph

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The Paragraph type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|Paragraph()|Initializes a new instance of the Paragraph class with default properties.|
|Paragraph(para)|Initializes a new instance of the Paragraph class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|portions|Returns the collection of a text portions.<br/>            Read-only [IPortionCollection](/python/aspose.slides/iportioncollection/).|
|paragraph_format|Returns the formatting object for this paragraph.<br/>            Read-only [IParagraphFormat](/python/aspose.slides/iparagraphformat/).|
|text|Gets or sets the the plain text of a paragraph.<br/>            Read/write string.|
|end_paragraph_portion_format|Specifies the portion properties that are to be used if another portion is inserted after <br/>            the last one.|
|as_islide_component|Allows to get base ISlideComponent interface.<br/>            Read-only [ISlideComponent](/python/aspose.slides/islidecomponent/).|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/python/aspose.slides/ibaseslide/).|
|as_ipresentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/python/aspose.slides/ipresentationcomponent/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/python/aspose.slides/ipresentation/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|join_portions_with_same_formatting()|Joins runs with same formatting.|
|get_rect()|Get coordinates of rect that bounds paragraph. The rect includes all the lines of<br/>            text in paragraph, including empty ones.|
