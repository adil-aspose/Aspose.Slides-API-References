---
title: Table
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 10290
url: /net/aspose.slides/table/
---
## Table class

Represents a table on a slide.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Public Members

| name | description |
| --- | --- |
| [Columns](columns) { get; } | Returns the collectoin of columns. Read-only [`IColumnCollection`](../icolumncollection). |
| [FirstCol](firstcol) { get; set; } | Determines whether the first column of a table has to be drawn with a special formatting. Read/write Boolean. |
| [FirstRow](firstrow) { get; set; } | Determines whether the first row of a table has to be drawn with a special formatting. Read/write Boolean. |
| [HorizontalBanding](horizontalbanding) { get; set; } | Determines whether the even rows has to be drawn with a different formatting. Read/write Boolean. |
| [Item](item) { get; } | Returns the cell at the specified column and row indexes. Read-only [`Cell`](../cell). |
| [LastCol](lastcol) { get; set; } | Determines whether the last column of a table has to be drawn with a special formatting. Read/write Boolean. |
| [LastRow](lastrow) { get; set; } | Determines whether the last row of a table has to be drawn with a special formatting. Read/write Boolean. |
| [RightToLeft](righttoleft) { get; set; } | Determines whether the table has right to left reading order. Read-write Boolean. |
| [Rows](rows) { get; } | Returns the collectoin of rows. Read-only [`IRowCollection`](../irowcollection). |
| [StylePreset](stylepreset) { get; set; } | Gets or sets builtin table style. Read/write [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](tableformat) { get; } | Returns the TableFormat object that contains formatting properties for this table. Read-only [`ITableFormat`](../itableformat). |
| [VerticalBanding](verticalbanding) { get; set; } | Determines whether the even columns has to be drawn with a different formatting. Read/write Boolean. |
| [MergeCells](mergecells)(…) | Merges neighbour cells. |
| [SetTextFormat](settextformat)(…) | Sets defined portion format properties to all table cells' portions. (3 methods) |

### See Also

* class [GraphicalObject](../graphicalobject)
* interface [ITable](../itable)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
