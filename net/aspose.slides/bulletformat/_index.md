---
title: BulletFormat
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 970
url: /net/aspose.slides/bulletformat/
---
## BulletFormat class

Represents paragraph bullet formatting properties.

```csharp
public class BulletFormat : PVIObject, IBulletFormat
```

## Public Members

| name | description |
| --- | --- |
| [Char](char) { get; set; } | Returns or sets the bullet char of a paragraph with no inheritance. Read/write Char. |
| [Color](color) { get; } | Returns the color format of a bullet of a paragraph with no inheritance. Read-only [`IColorFormat`](../icolorformat). |
| [Font](font) { get; set; } | Returns or sets the bullet font of a paragraph with no inheritance. Read/write [`IFontData`](../ifontdata). |
| [Height](height) { get; set; } | Returns or sets the bullet height of a paragraph with no inheritance. Value float.NaN determines that bullet inherits height from the first portion in the paragraph. Read/write Single. |
| [IsBulletHardColor](isbullethardcolor) { get; set; } | Determines whether the bullet has own color or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own color and NullableBool.False if bullet inherits color from the first portion in the paragraph. Read/write [`NullableBool`](../nullablebool). |
| [IsBulletHardFont](isbullethardfont) { get; set; } | Determines whether the bullet has own font or inherits it from the first portion in the paragraph. NullableBool.True if bullet has own font and NullableBool.False if bullet inherits font from the first portion in the paragraph. Read/write [`NullableBool`](../nullablebool). |
| [NumberedBulletStartWith](numberedbulletstartwith) { get; set; } | Returns or sets the first number which is used for group of numbered bullets with no inheritance. Read/write Int16. |
| [NumberedBulletStyle](numberedbulletstyle) { get; set; } | Returns or sets the style of a numbered bullet with no inheritance. Read/write [`NumberedBulletStyle`](../numberedbulletstyle). |
| [Picture](picture) { get; } | Returns the picture used as a bullet in a paragraph with no inheritance. Read-only [`ISlidesPicture`](../islidespicture). |
| [Type](type) { get; set; } | Returns or sets the bullet type of a paragraph with no inheritance. Read/write [`BulletType`](../bullettype). |
| [ApplyDefaultParagraphIndentsShifts](applydefaultparagraphindentsshifts)() | Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values). |
| [GetEffective](geteffective)() | Gets effective bullet formatting data with the inheritance applied. |

### See Also

* class [PVIObject](../pviobject)
* interface [IBulletFormat](../ibulletformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->