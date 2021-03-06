---
title: GeometryShape Class
type: docs
weight: 610
url: /python/aspose.slides/geometryshape/
---

Represents the parent class for all geometric shapes.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.GeometryShape

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The GeometryShape type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|is_text_holder|Determines whether the shape is TextHolder_PPT.<br/>            Read-only bool.|
|placeholder|Returns the placeholder for a shape. Returns null if the shape has no placeholder.<br/>            Read-only [IPlaceholder](/python/aspose.slides/iplaceholder/).|
|custom_data|Returns the shape's custom data.<br/>            Read-only [ICustomData](/python/aspose.slides/icustomdata/).|
|raw_frame|Returns or sets the raw shape frame's properties.<br/>            Read/write [IShapeFrame](/python/aspose.slides/ishapeframe/).|
|frame|Returns or sets the shape frame's properties.<br/>            Read/write [IShapeFrame](/python/aspose.slides/ishapeframe/).|
|line_format|Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have line properties.<br/>            Read-only [ILineFormat](/python/aspose.slides/ilineformat/).|
|three_dformat|Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have 3d properties.<br/>            Read-only [IThreeDFormat](/python/aspose.slides/ithreedformat/).|
|effect_format|Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return null for certain types of shapes which don't have effect properties.<br/>            Read-only [IEffectFormat](/python/aspose.slides/ieffectformat/).|
|fill_format|Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have fill properties.<br/>            Read-only [IFillFormat](/python/aspose.slides/ifillformat/).|
|hyperlink_click|Returns or sets the hyperlink defined for mouse click.<br/>            Read/write [IHyperlink](/python/aspose.slides/ihyperlink/).|
|hyperlink_mouse_over|Returns or sets the hyperlink defined for mouse over.<br/>            Read/write [IHyperlink](/python/aspose.slides/ihyperlink/).|
|hyperlink_manager|Returns the hyperlink manager.<br/>            Read-only [IHyperlinkManager](/python/aspose.slides/ihyperlinkmanager/).|
|hidden|Determines whether the shape is hidden.<br/>            Read/write bool.|
|zorder_position|Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only|
|connection_site_count|Returns the number of connection sites on the shape.<br/>            Read-only|
|rotation|Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write|
|x|Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write|
|y|Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write|
|width|Returns or sets the width of the shape.<br/>            Read/write|
|height|Returns or sets the height of the shape.<br/>            Read/write|
|black_white_mode|Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write [BlackWhiteMode](/python/aspose.slides/blackwhitemode/).|
|unique_id|Gets unique shape identifier in presentation scope.<br/>            Read-only int.<br/>            See also [office_interop_shape_id](/python/aspose.slides/shape/) for getting unique shape identifier in slide scope.|
|office_interop_shape_id|Gets unique shape identifier in slide scope.<br/>            Read-only int.<br/>            See also [unique_id](/python/aspose.slides/shape/) for getting unique shape identifier in presentation scope.|
|alternative_text|Returns or sets the alternative text associated with a shape.<br/>            Read/write string.|
|alternative_text_title|Returns or sets the title of alternative text associated with a shape.<br/>            Read/write string.|
|name|Returns or sets the name of a shape.<br/>            Must be not null. Use empty string value if needed.<br/>            Read/write string.|
|shape_lock|Returns shape's locks.<br/>            Read-only [IBaseShapeLock](/python/aspose.slides/ibaseshapelock/).|
|is_grouped|Determines whether the shape is grouped.<br/>            Read-only bool.|
|parent_group|Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only [IGroupShape](/python/aspose.slides/igroupshape/).|
|slide|Returns the parent slide of a shape.<br/>            Read-only [IBaseSlide](/python/aspose.slides/ibaseslide/).|
|presentation|Returns the parent presentation of a slide.<br/>            Read-only [IPresentation](/python/aspose.slides/ipresentation/).|
|shape_style|Returns shape's style object.<br/>            Read-only [IShapeStyle](/python/aspose.slides/ishapestyle/).|
|shape_type|Returns or sets the geometry preset type.<br/>            Note: on value changing all adjustment values will reset to their default values.<br/>            Read/write [ShapeType](/python/aspose.slides/shapetype/).|
|adjustments|Returns a collection of shape's adjustment values.<br/>            Read-only [IAdjustValueCollection](/python/aspose.slides/iadjustvaluecollection/).|
|as_ihyperlink_container|Allows to get base IHyperlinkContainer interface.<br/>            Read-only [IHyperlinkContainer](/python/aspose.slides/ihyperlinkcontainer/).|
|as_islide_component|Allows to get base ISlideComponent interface.<br/>            Read-only [ISlideComponent](/python/aspose.slides/islidecomponent/).|
|as_ipresentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/python/aspose.slides/ipresentationcomponent/).|
|as_ishape|Allows to get base IShape interface.<br/>            Read-only [IShape](/python/aspose.slides/ishape/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|get_thumbnail()|Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.|
|get_thumbnail(bounds, scale_x, scale_y)|Returns shape thumbnail.|
|write_as_svg(stream)|Saves content of Shape as SVG file.|
|write_as_svg(stream, svg_options)|Saves content of Shape as SVG file.|
|remove_placeholder()|Defines that this shape isn't a placeholder.|
|add_placeholder(placeholder_to_copy_from)|Adds a new placeholder if there is no and sets placeholder properties to a specified one.|
|get_geometry_paths()|Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape.|
|set_geometry_path(geometry_path)|Updates shape geometry from [IGeometryPath](/python/aspose.slides/igeometrypath/) object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([shape_type](/python/aspose.slides/geometryshape/)) to [CUSTOM](/python/aspose.slides/shapetype/).|
|set_geometry_paths(geometry_paths)|Updates shape geometry from array of [IGeometryPath](/python/aspose.slides/igeometrypath/). Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([shape_type](/python/aspose.slides/geometryshape/)) to [CUSTOM](/python/aspose.slides/shapetype/).|
|create_shape_elements()|Creates and returns array of shape's elements.|
