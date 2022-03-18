---
title: SecondaryCategories
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 120
url: /net/aspose.slides.charts/chartdata/secondarycategories/
---
## ChartData.SecondaryCategories property

Gets the secondary categories if [`UseSecondaryCategories`](../usesecondarycategories) property is true. Read-only [`IChartCategoryCollection`](../../ichartcategorycollection).

```csharp
public IChartCategoryCollection SecondaryCategories { get; }
```

## Remarks

If [`UseSecondaryCategories`](../usesecondarycategories) property is false then this `SecondaryCategories` property return null and data in [`Categories`](../categories) property is used both for primary and secondary series. If [`UseSecondaryCategories`](../usesecondarycategories) property is true then data in this `SecondaryCategories` property is used for secondary series and data in [`Categories`](../categories) property is used for primary series.

## Examples

Example. What categories are related to series - ChartData.Categories or ChartData.SecondaryCategories?

```csharp
if (series.PlotOnSecondAxis && series.Chart.ChartData.UseSecondaryCategories)
{
    // related categories are series.Chart.ChartData.SecondaryCategories
}
else
{
    // related categories are series.Chart.ChartData.Categories
}
```

### See Also

* interface [IChartCategoryCollection](../../ichartcategorycollection)
* class [ChartData](../../chartdata)
* namespace [Aspose.Slides.Charts](../../chartdata)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->