---
title: Cell Class
type: docs
weight: 200
url: /python/aspose.slides/cell/
---

Represents a cell of a table.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.Cell

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The Cell type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|offset_x|Returns a distance from left side of a table to left side of a cell.<br/>            Read-only float.|
|offset_y|Returns a distance from top side of a table to top side of a cell.<br/>            Read-only float.|
|first_row_index|Returns an index of first row, covered by the cell.<br/>            Read-only|
|first_column_index|Returns an index of first column, covered by the cell.<br/>            Read-only|
|width|Returns the width of the cell.<br/>            Read-only float.|
|height|Returns the height of the cell.<br/>            Read-only float.|
|minimal_height|Returns the minimum height of a cell.<br/>            This is a sum of minimal heights of all rows cowered by the cell.<br/>            Read-only float.|
|margin_left|Returns or sets the left margin in a TextFrame.<br/>            Read/write float.|
|margin_right|Returns or sets the right margin in a TextFrame.<br/>            Read/write float.|
|margin_top|Returns or sets the top margin in a TextFrame.<br/>            Read/write float.|
|margin_bottom|Returns or sets the bottom margin in a TextFrame.<br/>            Read/write float.|
|text_vertical_type|Returns or sets the type of vertical text.<br/>            Read/write [TextVerticalType](/python/aspose.slides/textverticaltype/).|
|text_anchor_type|Returns or sets the text anchor type.<br/>            Read/write [TextAnchorType](/python/aspose.slides/textanchortype/).|
|anchor_center|Determines whether or not text box centered inside a cell.<br/>            Read/write bool.|
|first_row|Gets first row of cell.<br/>            Read-only [IRow](/python/aspose.slides/irow/).|
|first_column|Gets first column of cell.<br/>            Read-only [IColumn](/python/aspose.slides/icolumn/).|
|col_span|Returns the number of grid columns in the parent table's table grid<br/>            which shall be spanned by the current cell. This property allows cells<br/>            to have the appearance of being merged, as they span vertical boundaries<br/>            of other cells in the table.<br/>            Read-only|
|row_span|Returns the number of rows that a merged cell spans. This is used in combination<br/>            with the vMerge attribute on other cells in order to specify the beginning cell<br/>            of a horizontal merge.<br/>            Read-only|
|text_frame|Returns the text frame of a cell.<br/>            Read-only [ITextFrame](/python/aspose.slides/itextframe/).|
|table|Returns the parent Table object for a cell.<br/>            Read-only [ITable](/python/aspose.slides/itable/).|
|is_merged_cell|Returns true if the cell is merged with any adjusted cell, false otherwise.<br/>            Read-only bool.|
|cell_format|Returns the CellFormat object that contains formatting properties for this cell.<br/>            Read-only [ICellFormat](/python/aspose.slides/icellformat/).|
|slide|Returns the parent slide of a cell.<br/>            Read-only [IBaseSlide](/python/aspose.slides/ibaseslide/).|
|presentation|Returns the parent presentation of a cell.<br/>            Read-only [IPresentation](/python/aspose.slides/ipresentation/).|
|as_islide_component|Allows to get base ISlideComponent interface.<br/>            Read-only [ISlideComponent](/python/aspose.slides/islidecomponent/).|
|as_ipresentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/python/aspose.slides/ipresentationcomponent/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|split_by_col_span(index)|Splits the cell to two cells by index of column.|
|split_by_row_span(index)|Splits the cell to two cells by index of row.|
|split_by_height(height)|Splits the cell by height.|
|split_by_width(width)|Splits the cell by width.|
