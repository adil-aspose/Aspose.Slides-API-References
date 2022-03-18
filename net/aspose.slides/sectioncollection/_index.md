---
title: SectionCollection
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 9270
url: /net/aspose.slides/sectioncollection/
---
## SectionCollection class

Represents a collection of sections.

```csharp
public sealed class SectionCollection : ISectionCollection
```

## Public Members

| name | description |
| --- | --- |
| [Count](count) { get; } | Gets the number of elements actually contained in the collection. Read-only Int32. |
| [IsSynchronized](issynchronized) { get; } | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only Boolean. |
| [Item](item) { get; } | Gets the element at the specified index. Read-only [`ISection`](../isection). |
| [SyncRoot](syncroot) { get; } | Returns a synchronization root. Read-only Object. |
| [AddEmptySection](addemptysection)(…) | Add empty section to specified position of the collection. |
| [AddSection](addsection)(…) | Add slides section started form specific slide. |
| [AppendEmptySection](appendemptysection)(…) | Add empty section to the end of the collection. |
| [Clear](clear)() | Removes all sections from the collection. |
| [CopyTo](copyto)(…) | Copies the entire collection to the specified array. |
| [GetEnumerator](getenumerator)() | Returns an enumerator that iterates through the collection. |
| [IndexOf](indexof)(…) | Returns an index of the specified section in the collection. |
| [RemoveSection](removesection)(…) | Remove section. Slides contained in the section will be merged into previous section. |
| [RemoveSectionWithSlides](removesectionwithslides)(…) | Remove section and slides contained in the section. |
| [ReorderSectionWithSlides](reordersectionwithslides)(…) | Moves section and its slides from the collection to the specified position. |

### See Also

* interface [ISectionCollection](../isectioncollection)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->