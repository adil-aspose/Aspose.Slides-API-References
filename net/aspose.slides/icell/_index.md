---
title: ICell
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 5200
url: /net/aspose.slides/icell/
---
## ICell interface

Represents a cell in a table.

```csharp
public interface ICell : ISlideComponent
```

## Members

| name | description |
| --- | --- |
| [AnchorCenter](anchorcenter) { get; set; } | Determines whether or not text box centered inside a cell. Read/write Boolean. |
| [AsISlideComponent](asislidecomponent) { get; } | Allows to get base ISlideComponent interface. Read-only [`ISlideComponent`](../islidecomponent). |
| [CellFormat](cellformat) { get; } | Returns the CellFormat object that contains formatting properties for this cell. Read-only [`ICellFormat`](../icellformat). |
| [ColSpan](colspan) { get; } | Returns the number of grid columns in the parent table's table grid which shall be spanned by the current cell. This property allows cells to have the appearance of being merged, as they span vertical boundaries of other cells in the table. Read-only Int32. |
| [FirstColumn](firstcolumn) { get; } | Gets first column of cell. Read-only [`IColumn`](../icolumn). |
| [FirstColumnIndex](firstcolumnindex) { get; } | Returns an index of first column, covered by the cell. Read-only Int32. |
| [FirstRow](firstrow) { get; } | Gets first row of cell. Read-only [`IRow`](../irow). |
| [FirstRowIndex](firstrowindex) { get; } | Returns an index of first row, covered by the cell. Read-only Int32. |
| [Height](height) { get; } | Returns the height of the cell. Read-only Double. |
| [IsMergedCell](ismergedcell) { get; } | Returns true if the cell is merged with any adjusted cell, false otherwise. Read-only Boolean. |
| [MarginBottom](marginbottom) { get; set; } | Returns or sets the bottom margin in a TextFrame. Read/write Double. |
| [MarginLeft](marginleft) { get; set; } | Returns or sets the left margin in a TextFrame. Read/write Double. |
| [MarginRight](marginright) { get; set; } | Returns or sets the right margin in a TextFrame. Read/write Double. |
| [MarginTop](margintop) { get; set; } | Returns or sets the top margin in a TextFrame. Read/write Double. |
| [MinimalHeight](minimalheight) { get; } | Returns the minimum height of a cell. This is a sum of minimal heights of all rows cowered by the cell. Read-only Double. |
| [OffsetX](offsetx) { get; } | Returns a distance from left side of a table to left side of a cell. Read-only Double. |
| [OffsetY](offsety) { get; } | Returns a distance from top side of a table to top side of a cell. Read-only Double. |
| [RowSpan](rowspan) { get; } | Returns the number of rows that a merged cell spans. This is used in combination with the vMerge attribute on other cells in order to specify the beginning cell of a horizontal merge. Read-only Int32. |
| [Table](table) { get; } | Returns the parent Table object for a cell. Read-only [`ITable`](../itable). |
| [TextAnchorType](textanchortype) { get; set; } | Returns or sets the text anchor type. Read/write [`TextAnchorType`](../textanchortype). |
| [TextFrame](textframe) { get; } | Returns the text frame of a cell. Read-only [`ITextFrame`](../itextframe). |
| [TextVerticalType](textverticaltype) { get; set; } | Returns or sets the type of vertical text. Read/write [`TextVerticalType`](../textverticaltype). |
| [Width](width) { get; } | Returns the width of the cell. Read-only Double. |
| [SplitByColSpan](splitbycolspan)(…) | Splits the cell to two cells by index of column. |
| [SplitByHeight](splitbyheight)(…) | Splits the cell by height. |
| [SplitByRowSpan](splitbyrowspan)(…) | Splits the cell to two cells by index of row. |
| [SplitByWidth](splitbywidth)(…) | Splits the cell by width. |

### See Also

* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->