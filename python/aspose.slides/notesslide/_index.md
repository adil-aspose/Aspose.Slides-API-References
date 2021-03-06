---
title: NotesSlide Class
type: docs
weight: 3150
url: /python/aspose.slides/notesslide/
---

Represents a notes slide in a presentation.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.NotesSlide

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The NotesSlide type exposes the following members:
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
|header_footer_manager|Returns HeaderFooter manager of the notes slide.<br/>            Read-only [INotesSlideHeaderFooterManager](/python/aspose.slides/inotesslideheaderfootermanager/).|
|notes_text_frame|Returns a TextFrame with notes' text if there is one.<br/>            Read-only [ITextFrame](/python/aspose.slides/itextframe/).|
|theme_manager|Returns the overriding theme manager.<br/>            Read-only [IOverrideThemeManager](/python/aspose.slides.theme/ioverridethememanager/).|
|parent_slide|Returns the parent slide.<br/>            Read-only [ISlide](/python/aspose.slides/islide/).|
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
