---
title: ChartDataCell
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 1200
url: /net/aspose.slides.charts/chartdatacell/
---
## ChartDataCell class

Represents cell for chart data.

```csharp
public class ChartDataCell : IChartDataCell
```

## Public Members

| name | description |
| --- | --- |
| [ChartDataWorksheet](chartdataworksheet) { get; } | Gets the worksheet. Read-only [`IChartDataWorksheet`](../ichartdataworksheet). |
| [Column](column) { get; } | Returns the index of the column of worksheet in which the cell is located. Read-only Int32. |
| [CustomNumberFormat](customnumberformat) { get; set; } | Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String. |
| [Formula](formula) { get; set; } | Gets or sets the formula in A1-style. |
| [IsHidden](ishidden) { get; } | Determines whether the cell is hidden. Read-only Boolean. |
| [PresetNumberFormat](presetnumberformat) { get; set; } | Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]". Read/write Byte. |
| [R1C1Formula](r1c1formula) { get; set; } | Gets or sets the formula in R1C1-style. |
| [Row](row) { get; } | Returns the index of the row of worksheet in which the cell is located. Read-only Int32. |
| [Value](value) { get; set; } | Gets or sets the value. Read/write Object. |
| [Calculate](calculate)(…) | If the cell contains a formula, the value will be updated base on that formula. |

### See Also

* interface [IChartDataCell](../ichartdatacell)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->