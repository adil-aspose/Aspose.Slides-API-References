---
title: IChartData
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 1680
url: /net/aspose.slides.charts/ichartdata/
---
## IChartData interface

Represents data used for a chart plotting.

```csharp
public interface IChartData
```

## Members

| name | description |
| --- | --- |
| [Categories](categories) { get; } | Gets the primary categories (or both primary and secondary categories if [`UseSecondaryCategories`](./usesecondarycategories) property is false). Read-only [`IChartCategoryCollection`](../ichartcategorycollection). |
| [ChartDataWorkbook](chartdataworkbook) { get; } | Gets the cells factory to create cells used for chart series or categories. Read-only [`IChartDataWorkbook`](../ichartdataworkbook). |
| [DataSourceType](datasourcetype) { get; } | Represents data source of the chart |
| [ExternalWorkbookPath](externalworkbookpath) { get; } | Represents external workbook path if data source is external, null otherwise |
| [SecondaryCategories](secondarycategories) { get; } | Gets the secondary categories if [`UseSecondaryCategories`](./usesecondarycategories) property is true. Read-only [`IChartCategoryCollection`](../ichartcategorycollection). |
| [Series](series) { get; } | Gets the series. Read-only [`IChartSeriesCollection`](../ichartseriescollection). |
| [SeriesGroups](seriesgroups) { get; } | Gets the groups of series. Read-only [`IChartSeriesGroupCollection`](../ichartseriesgroupcollection). |
| [UseSecondaryCategories](usesecondarycategories) { get; set; } | If false then [`SecondaryCategories`](./secondarycategories) property return null and data in [`Categories`](./categories) property is used both for primary and secondary series. If true then data in [`SecondaryCategories`](./secondarycategories) property is used for secondary series and data in [`Categories`](./categories) property is used for primary series. Read/write Boolean. |
| [GetRange](getrange)() | Gets chart data range. |
| [ReadWorkbookStream](readworkbookstream)() | Writes the internally contained Excel workbook it into an in-memory stream. |
| [SetExternalWorkbook](setexternalworkbook)(…) | Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook. (2 methods) |
| [SetRange](setrange)(…) | Set chart data range. Series and categories will be updated based on new data range. If amount of series in data range greater than count of series in the chart data then additional series with the same type as a last series in the current collection will be added to the end of the collection. |
| [SwitchRowColumn](switchrowcolumn)() | Swap the data over the axis. Data being charted on the X axis will move to the Y axis and vice versa. |
| [WriteWorkbookStream](writeworkbookstream)(…) | Initializes the internally contained Excel workbook with user-specified value. |

### See Also

* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
