---
title: CommentCollection Class
type: docs
weight: 320
url: /python/aspose.slides/commentcollection/
---

Represents a collection of comments of one author.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.CommentCollection

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The CommentCollection type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|as_icollection|Returns ICollection class.|
|as_ienumerable|Returns IEnumerable class.|
## **Indexer**
|**Name**|**Description**|
| :- | :- |
|[index]|Gets the element at the specified index.<br/>            Read-only [Comment](/python/aspose.slides/comment/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|to_array()|Creates and returns an array with all comments.|
|to_array(start_index, count)|Creates and returns an array with all comments from the specified range.|
|add_comment(text, slide, position, creation_time)|Add new comment at the end of a collection.|
|add_modern_comment(text, slide, shape, position, creation_time)|Add new modern comment at the end of a collection.|
|insert_comment(index, text, slide, position, creation_time)|Insert new comment to a collection at the specified index.|
|insert_modern_comment(index, text, slide, shape, position, creation_time)|Insert new modern comment to a collection at the specified index.|
|remove_at(index)|Removes the element at the specified index in a collection.|
|remove(comment)|Removes the first occurrence of the specified comment in a collection.|
|clear()|Removes all comments from a collection.|
|find_comment_by_idx(idx)|Finds a comment in the collection by index.|
