---
title: IParagraphFormatEffectiveData
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 6290
url: /net/aspose.slides/iparagraphformateffectivedata/
---
## IParagraphFormatEffectiveData interface

Immutable object which contains effective paragraph formatting properties.

```csharp
public interface IParagraphFormatEffectiveData
```

## Members

| name | description |
| --- | --- |
| [Alignment](alignment) { get; } | Returns the text alignment in a paragraph. Read-only [`TextAlignment`](../textalignment). |
| [Bullet](bullet) { get; } | Returns a bullet format of a paragraph. Read-only [`IBulletFormatEffectiveData`](../ibulletformateffectivedata). |
| [DefaultPortionFormat](defaultportionformat) { get; } | Returns default portion format of a paragraph. Read-only [`IPortionFormatEffectiveData`](../iportionformateffectivedata). |
| [DefaultTabSize](defaulttabsize) { get; } | Returns default tabulation size. Read-only Single. |
| [Depth](depth) { get; } | Returns a depth of a paragraph. Read-only Int16. |
| [EastAsianLineBreak](eastasianlinebreak) { get; } | Determines whether the East Asian line break is used in a paragraph. Read-only Boolean. |
| [FontAlignment](fontalignment) { get; } | Returns a font alignment in a paragraph. Read-only [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](hangingpunctuation) { get; } | Determines whether the hanging punctuation is used in a paragraph. Read-only Boolean. |
| [Indent](indent) { get; } | Returns paragraph First Line Indent/Hanging Indent. Hanging Indent can be defined with negative values. Read-only Single. |
| [LatinLineBreak](latinlinebreak) { get; } | Determines whether the Latin line break is used in a paragraph. Read-only Boolean. |
| [MarginLeft](marginleft) { get; } | Returns the left margin in a paragraph. Read-only Single. |
| [MarginRight](marginright) { get; } | Returns the right margin in a paragraph. Read-only Single. |
| [RightToLeft](righttoleft) { get; } | Determines whether the Right to Left writing is used in a paragraph. Read-only Boolean. |
| [SpaceAfter](spaceafter) { get; } | Returns the amount of space after the last line in a paragraph. Read-only Single. |
| [SpaceBefore](spacebefore) { get; } | Returns the amount of space before the first line in a paragraph. Read-only Single. |
| [SpaceWithin](spacewithin) { get; } | Returns the amount of space between base lines in a paragraph. Read-only Single. |
| [Tabs](tabs) { get; } | Returns tabulations of a paragraph. Read-only [`ITabEffectiveData`](../itabeffectivedata)[]. |

## Remarks

This interface is used together with the [`IParagraphFormat`](../iparagraphformat) interface to return effective formatting values with inheritance applied.

### See Also

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
