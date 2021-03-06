---
title: LayoutSlide Class
type: docs
weight: 2930
url: /python/aspose.slides/layoutslide/
---

Represents a layout slide.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.LayoutSlide

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The LayoutSlide type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|shapes|Returns the shapes of a slide.<br/>            Read-only [IShapeCollection](/python/aspose.slides/ishapecollection/).|
|controls|Returns the collection of ActiveX controls on a slide.<br/>            Read-only [IControlCollection](/python/aspose.slides/icontrolcollection/).|
|name|Returns or sets the name of a slide.<br/>            Read/write string.|
|slide_id|Returns the ID of a slide.<br/>            Read-only int.|
|custom_data|Returns the slide's custom data.<br/>            Read-only [ICustomData](/python/aspose.slides/icustomdata/).|
|timeline|Returns animation timeline object.<br/>            Read-only [IAnimationTimeLine](/python/aspose.slides/ianimationtimeline/).|
|slide_show_transition|Returns the Transition object which contains information about<br/>            how the specified slide advances during a slide show.<br/>            Read-only [ISlideShowTransition](/python/aspose.slides/islideshowtransition/).|
|background|Returns slide's background.<br/>            Read-only [IBackground](/python/aspose.slides/ibackground/).|
|hyperlink_queries|Provides easy access to contained hyperlinks.<br/>            Read-only [IHyperlinkQueries](/python/aspose.slides/ihyperlinkqueries/).|
|show_master_shapes|Specifies if shapes on the master slide should be shown on slides or not.<br/>            Read/write bool.|
|presentation|Returns IPresentation interface.<br/>            Read-only [IPresentation](/python/aspose.slides/ipresentation/).|
|header_footer_manager|Returns HeaderFooter manager of the layout slide.<br/>            Read-only [ILayoutSlideHeaderFooterManager](/python/aspose.slides/ilayoutslideheaderfootermanager/).|
|master_slide|Returns or sets the master slide for a layout.<br/>            Read/write [IMasterSlide](/python/aspose.slides/imasterslide/).|
|theme_manager|Returns the overriding theme manager.<br/>            Read-only [IOverrideThemeManager](/python/aspose.slides.theme/ioverridethememanager/).|
|layout_type|Returns layout type of this layout slide.<br/>            Read-only [SlideLayoutType](/python/aspose.slides/slidelayouttype/).|
|has_depending_slides|Returns true if there exists at least one slide that depends on this layout slide.<br/>            Read-only bool.|
|as_islide_component|Returns ISlideComponent interface.<br/>            Read-only [ISlideComponent](/python/aspose.slides/islidecomponent/).|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/python/aspose.slides/ibaseslide/).|
|as_ipresentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/python/aspose.slides/ipresentationcomponent/).|
|as_ibase_slide|Allows to get base IBaseSlide interface.<br/>            Read-only [IBaseSlide](/python/aspose.slides/ibaseslide/).|
|as_ioverride_themeable|Returns IOverrideThemeable interface.<br/>            Read-only [IOverrideThemeable](/python/aspose.slides.theme/ioverridethemeable/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|join_portions_with_same_formatting()|Joins runs with same formatting in all paragraphs all acceptable shapes.|
|join_portions_with_same_formatting(collection)|Joins runs with same formatting in all paragraphs in all acceptable shapes.|
|equals(slide)|Determines whether the two IBaseSlide instances are equal.<br/>            Returning value is calculated based on slide's structure and static content.<br/>            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder.|
|create_theme_effective()|Returns an effective theme for this slide.|
|find_shape_by_alt_text(alt_text)|Finds first occurrence of a shape with the specified alternative text.|
|remove()|Removes layout from presentation.|
|get_depending_slides()|Returns an array with all slides, which depend on this layout slide.|
