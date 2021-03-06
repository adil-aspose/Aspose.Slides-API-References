---
title: IMathElementCollection
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 7770
url: /net/aspose.slides.mathtext/imathelementcollection/
---
## IMathElementCollection interface

Represents a collection of mathematical elements (MathElement).

```csharp
public interface IMathElementCollection : IEnumerable<IMathElement>
```

## Members

| name | description |
| --- | --- |
| [AsIEnumerable](asienumerable) { get; } | Returns IEnumerable interface. Read-only IEnumerable. |
| [Count](count) { get; } | Gets the number of elements actually contained in the collection. Read-only Int32. |
| [Item](item) { get; } | Gets the element at the specified index. Read-only [`IMathElement`](../imathelement). |
| [Add](add)(…) | Adds a math element to the end of the collection. |
| [Clear](clear)() | Removes all elements from the collection. |
| [Contains](contains)(…) | Determines whether the collection contains a specific value. |
| [CopyTo](copyto)(…) | Copy to specified array. |
| [IndexOf](indexof)(…) | Determines the index of a specific math element in collection. |
| [Insert](insert)(…) | Inserts a math element into the collection at the specified index. |
| [Remove](remove)(…) | Removes the first occurrence of a specific object from the collection. |
| [RemoveAt](removeat)(…) | Removes the element at the specified index of the collection. |

## Examples

Example:

```csharp
[C#]
IMathElementCollection collection = new MathBlock();
```

### See Also

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
