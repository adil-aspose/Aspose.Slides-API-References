---
title: OverrideTheme
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 10890
url: /net/aspose.slides.theme/overridetheme/
---
## OverrideTheme class

Represents a overriding theme.

```csharp
public class OverrideTheme : Theme, IOverrideTheme
```

## Public Members

| name | description |
| --- | --- |
| override [ColorScheme](colorscheme) { get; } | Returns the color scheme. Read-only [`IColorScheme`](../icolorscheme). |
| override [FontScheme](fontscheme) { get; } | Returns the font scheme. Read-only [`IFontScheme`](../ifontscheme). |
| override [FormatScheme](formatscheme) { get; } | Returns the shape format scheme. Read-only [`IFormatScheme`](../iformatscheme). |
| [IsEmpty](isempty) { get; } | True value means that ColorScheme, FontScheme, FormatScheme is null and any overriding with this theme object are disabled. Read-only Boolean. |
| [Clear](clear)() | Set ColorScheme, FontScheme, FormatScheme to null to disable any overriding with this theme object. |
| [InitColorScheme](initcolorscheme)() | Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. |
| [InitColorSchemeFrom](initcolorschemefrom)(…) | Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. |
| [InitColorSchemeFromInherited](initcolorschemefrominherited)() | Init ColorScheme with new object for overriding ColorScheme of InheritedTheme. And initialize data of this new object with data of the ColorScheme of InheritedTheme. |
| [InitFontScheme](initfontscheme)() | Init FontScheme with new object for overriding FontScheme of InheritedTheme. |
| [InitFontSchemeFrom](initfontschemefrom)(…) | Init FontScheme with new object for overriding FontScheme of InheritedTheme. |
| [InitFontSchemeFromInherited](initfontschemefrominherited)() | Init FontScheme with new object for overriding FontScheme of InheritedTheme. And initialize data of this new object with data of the FontScheme of InheritedTheme. |
| [InitFormatScheme](initformatscheme)() | Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. |
| [InitFormatSchemeFrom](initformatschemefrom)(…) | Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. |
| [InitFormatSchemeFromInherited](initformatschemefrominherited)() | Init FormatScheme with new object for overriding FormatScheme of InheritedTheme. And initialize data of this new object with data of the FormatScheme of InheritedTheme. |

### See Also

* class [Theme](../theme)
* interface [IOverrideTheme](../ioverridetheme)
* namespace [Aspose.Slides.Theme](../../aspose.slides.theme)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
