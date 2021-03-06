---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 5090
url: /net/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData interface

Base interface for immutable objects which contain effective text portion formatting properties.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Members

| name | description |
| --- | --- |
| [AlternativeLanguageId](alternativelanguageid) { get; } | Returns the Id of an alternative language. Read-only String. |
| [ComplexScriptFont](complexscriptfont) { get; } | Returns the complex script font info. Read-only [`IFontData`](../ifontdata). |
| [EastAsianFont](eastasianfont) { get; } | Returns the East Asian font info. Read-only [`IFontData`](../ifontdata). |
| [EffectFormat](effectformat) { get; } | Returns the text EffectFormat properties. Read-only [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](escapement) { get; } | Returns the superscript or subscript text. Value from -100% (subscript) to 100% (superscript). Read-only Single. |
| [FillFormat](fillformat) { get; } | Returns the text FillFormat properties. Read-only [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](fontbold) { get; } | Determines whether the font is bold. Read-only Boolean. |
| [FontHeight](fontheight) { get; } | Returns the font height of a portion. Read-only Single. |
| [FontItalic](fontitalic) { get; } | Determines whether the font is itallic. Read-only Boolean. |
| [FontUnderline](fontunderline) { get; } | Returns the text underline type. Read-only [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](highlightcolor) { get; } | Returns the color used to highlight a text. Read-only Color. |
| [IsHardUnderlineFill](ishardunderlinefill) { get; } | Determines whether the underline style has own FillFormat properties or inherits it from the FillFormat properties of the text. Read-only Boolean. |
| [IsHardUnderlineLine](ishardunderlineline) { get; } | Determines whether the underline style has own LineFormat properties or inherits it from the LineFormat properties of the text. Read-only Boolean. |
| [KerningMinimalSize](kerningminimalsize) { get; } | Returns the minimal font size, for which kerning should be switched on. Read-only Single. |
| [Kumimoji](kumimoji) { get; } | Determines whether the numbers should ignore text eastern language-specific vertical text layout. Read-only Boolean. |
| [LanguageId](languageid) { get; } | Returns the Id of a language. Read-only String. |
| [LatinFont](latinfont) { get; } | Returns the Latin font info. Read-only [`IFontData`](../ifontdata). |
| [LineFormat](lineformat) { get; } | Returns the LineFormat properties for text outlining. Read-only [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](normaliseheight) { get; } | Determines whether the height of a text should be normalized. Read-only Boolean. |
| [ProofDisabled](proofdisabled) { get; } | Determines whether the text shouldn't be proofed. Read-only Boolean. |
| [SmartTagClean](smarttagclean) { get; } | Determines whether the smart tag should be cleaned. Read-only Boolean. |
| [Spacing](spacing) { get; } | Returns the intercharacter spacing increment. Read-only Single. |
| [StrikethroughType](strikethroughtype) { get; } | Returns the strikethrough type of a text. Read-only [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](symbolfont) { get; } | Returns the symbolic font info. Read-only [`IFontData`](../ifontdata). |
| [TextCapType](textcaptype) { get; } | Returns the type of text capitalization. Read-only [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](underlinefillformat) { get; } | Returns the underline line FillFormat properties. Read-only [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](underlinelineformat) { get; } | Returns the LineFormat properties used to outline underline line. Read-only [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### See Also

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
