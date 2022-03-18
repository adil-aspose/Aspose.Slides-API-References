---
title: AddModernComment
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 20
url: /net/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection.AddModernComment method

Add new modern comment at the end of a collection.

```csharp
public IModernComment AddModernComment(string text, ISlide slide, IShape shape, PointF position, 
    DateTime creationTime)
```

| parameter | description |
| --- | --- |
| text | Plain text of a new modern comment. |
| slide | Slide in a presentation where to add a new modern comment. |
| shape | Shape on a slide to which a new modern comment is associated. |
| position | Position on a slide where to add a new modern comment. |
| creationTime | Time of a modern comment creation. |

## Return Value

Added modern comment.

## Examples

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ICommentAuthor newAuthor = pres.CommentAuthors.AddAuthor("Some Author", "SA");
    newAuthor.Comments.AddModernComment("This is modern comment", pres.Slides[0], null, new PointF(100, 100), DateTime.Now);

    pres.Save(outPptxFileName, SaveFormat.Pptx);
}
```

### See Also

* interface [IModernComment](../../imoderncomment)
* interface [ISlide](../../islide)
* interface [IShape](../../ishape)
* interface [ICommentCollection](../../icommentcollection)
* namespace [Aspose.Slides](../../icommentcollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->