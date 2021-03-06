---
title: IZoomFrame Class
type: docs
weight: 2850
url: /python/aspose.slides/izoomframe/
---

Represents a Slide Zoom object in a slide.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.IZoomFrame

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The IZoomFrame type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|target_slide|Gets or sets the slide object that the Slide Zoom object links to.<br/>            Read/write [ISlide](/python/aspose.slides/islide/).|
|image_type|Gets or sets the image type of a zoom object.<br/>            Read/write [ZoomImageType](/python/aspose.slides/zoomimagetype/).<br/>            Default value: Preview|
|return_to_parent|Gets or sets the navigation behavior in slideshow.<br/>            Read/write bool.<br/>            Default value: false|
|show_background|Gets or sets value that specifies whether the Zoom will use the background of the destination slide.<br/>            Read/write bool.<br/>            Default value: true|
|image|Gets or sets image for zoom object.<br/>            Read/write [IPPImage](/python/aspose.slides/ippimage/).|
|transition_duration|Gets or sets the duration of the transition between Zoom and slide.<br/>            Read/write|
|as_igraphical_object|Allows to get base IGraphicalObject interface.<br/>            Read-only [IGraphicalObject](/python/aspose.slides/igraphicalobject/).|
|shape_lock|Returns shape's locks.<br/>            Read-only [IBaseShapeLock](/python/aspose.slides/ibaseshapelock/).|
|graphical_object_lock|Returns shape's locks.<br/>            Read-only [IGraphicalObjectLock](/python/aspose.slides/igraphicalobjectlock/).|
|as_ishape|Allows to get base IShape interface.<br/>            Read-only [IShape](/python/aspose.slides/ishape/).|
|is_text_holder|Determines whether the shape is TextHolder.<br/>            Read-only bool.|
|placeholder|Returns the placeholder for a shape.<br/>            Read-only [IPlaceholder](/python/aspose.slides/iplaceholder/).|
|custom_data|Returns the shape's custom data.<br/>            Read-only [ICustomData](/python/aspose.slides/icustomdata/).|
|raw_frame|Returns or sets the raw shape frame's properties.<br/>            Read/write [IShapeFrame](/python/aspose.slides/ishapeframe/).|
|frame|Returns or sets the shape frame's properties.<br/>            Read/write [IShapeFrame](/python/aspose.slides/ishapeframe/).|
|line_format|Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Read-only [ILineFormat](/python/aspose.slides/ilineformat/).|
|three_dformat|Returns the ThreeDFormat object that contains line formatting properties for a shape.<br/>            Read-only [IThreeDFormat](/python/aspose.slides/ithreedformat/).|
|effect_format|Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Read-only [IEffectFormat](/python/aspose.slides/ieffectformat/).|
|fill_format|Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Read-only [IFillFormat](/python/aspose.slides/ifillformat/).|
|hidden|Determines whether the shape is hidden.<br/>            Read/write bool.|
|zorder_position|Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only|
|connection_site_count|Returns the number of connection sites on the shape.<br/>            Read-only|
|rotation|Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write|
|x|Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write|
|y|Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write|
|width|Returns or sets the width of the shape.<br/>            Read/write|
|height|Returns or sets the height of the shape.<br/>            Read/write|
|alternative_text|Returns or sets the alternative text associated with a shape.<br/>            Read/write string.|
|alternative_text_title|Returns or sets the title of alternative text associated with a shape.<br/>            Read/write string.|
|name|Returns or sets the name of a shape.<br/>            Read/write string.|
|unique_id|Gets unique shape identifier in presentation scope.<br/>            Read-only int.<br/>            See also [office_interop_shape_id](/python/aspose.slides/ishape/) for getting unique shape identifier in slide scope.|
|office_interop_shape_id|Gets unique shape identifier in slide scope.<br/>            Read-only int.<br/>            See also [unique_id](/python/aspose.slides/ishape/) for getting unique shape identifier in presentation scope.|
|is_grouped|Determines whether the shape is grouped.<br/>            Read-only bool.|
|black_white_mode|Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write [BlackWhiteMode](/python/aspose.slides/blackwhitemode/).|
|parent_group|Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only [IGroupShape](/python/aspose.slides/igroupshape/).|
|as_ihyperlink_container|Allows to get base IHyperlinkContainer interface.<br/>            Read-only [IHyperlinkContainer](/python/aspose.slides/ihyperlinkcontainer/).|
|as_islide_component|Allows to get base ISlideComponent interface.<br/>            Read-only [ISlideComponent](/python/aspose.slides/islidecomponent/).|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/python/aspose.slides/ibaseslide/).|
|as_ipresentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/python/aspose.slides/ipresentationcomponent/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/python/aspose.slides/ipresentation/).|
|hyperlink_click|Returns or sets the hyperlink defined for mouse click.<br/>            Read/write [IHyperlink](/python/aspose.slides/ihyperlink/).|
|hyperlink_mouse_over|Returns or sets the hyperlink defined for mouse over.<br/>            Read/write [IHyperlink](/python/aspose.slides/ihyperlink/).|
|hyperlink_manager|Hyperlinks manager<br/>            Read-only [IHyperlinkManager](/python/aspose.slides/ihyperlinkmanager/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|get_thumbnail()|Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.|
|get_thumbnail(bounds, scale_x, scale_y)|Returns shape thumbnail.|
|write_as_svg(stream)|Saves content of Shape as SVG file.|
|write_as_svg(stream, svg_options)|Saves content of Shape as SVG file.|
|add_placeholder(placeholder_to_copy_from)|Adds a new placeholder if there is no and sets placeholder properties to a specified one.|
|remove_placeholder()|Defines that this shape isn't a placeholder.|
