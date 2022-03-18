---
title: Worksheets
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 50
url: /net/aspose.slides.charts/ichartdataworkbook/worksheets/
---
## IChartDataWorkbook.Worksheets property

Gets a collection of worksheets.

```csharp
public IChartDataWorksheetCollection Worksheets { get; }
```

## Examples

Example:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.Pie, 50, 50, 400, 500);
    IChartDataWorkbook workbook =  chart.ChartData.ChartDataWorkbook;
    foreach (IChartDataWorksheet worksheet in workbook.Worksheets)
    {
        string worksheetName = worksheet.Name;
    }
}
```

### See Also

* interface [IChartDataWorksheetCollection](../../ichartdataworksheetcollection)
* interface [IChartDataWorkbook](../../ichartdataworkbook)
* namespace [Aspose.Slides.Charts](../../ichartdataworkbook)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->