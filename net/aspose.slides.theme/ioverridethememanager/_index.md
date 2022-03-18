---
title: IOverrideThemeManager
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 10780
url: /net/aspose.slides.theme/ioverridethememanager/
---
## IOverrideThemeManager interface

Provides access to different types of overriden themes.

```csharp
public interface IOverrideThemeManager : IThemeManager
```

## Members

| name | description |
| --- | --- |
| [AsIThemeManager](asithememanager) { get; } | Allows to get base IThemeManager interface. Read-only [`IThemeManager`](../ithememanager). |
| [IsOverrideThemeEnabled](isoverridethemeenabled) { get; } | Determines whether OverrideTheme overrides inherited effective theme or not. To enable OverrideTheme for overriding use OverrideTheme.Init*() methods. To disable OverrideTheme from overriding use OverrideTheme.Clear() method. Read-only Boolean. |
| [OverrideTheme](overridetheme) { get; set; } | Returns the overriding theme object. Read/write [`IOverrideTheme`](../ioverridetheme). |

### See Also

* interface [IThemeManager](../ithememanager)
* namespace [Aspose.Slides.Theme](../../aspose.slides.theme)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->