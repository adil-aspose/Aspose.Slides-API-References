---
title: BaseOverrideThemeManager Class
type: docs
weight: 10
url: /python/aspose.slides.theme/baseoverridethememanager/
---

Base class for classes that provide access to different types of overriden themes.

**Namespace:** [aspose.slides.theme](/python/aspose.slides.theme/)

**Full Class Name:** aspose.slides.theme.BaseOverrideThemeManager

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The BaseOverrideThemeManager type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|override_theme|Returns the overriding theme object.<br/>            Read/write [IOverrideTheme](/python/aspose.slides.theme/ioverridetheme/).|
|is_override_theme_enabled|Determines whether OverrideTheme overrides inherited effective theme or not.<br/>            To enable OverrideTheme for overriding use OverrideTheme.Init*() methods.<br/>            To disable OverrideTheme from overriding use OverrideTheme.Clear() method.<br/>            Read-only bool.|
|as_itheme_manager|Allows to get base IThemeManager interface.<br/>            Read-only [IThemeManager](/python/aspose.slides.theme/ithememanager/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_theme_effective()|Returns the theme object.|
|apply_color_scheme(scheme)|Applies extra color scheme to a slide.|
