---
title: IChartCategory
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 1630
url: /net/aspose.slides.charts/ichartcategory/
---
## IChartCategory interface

Represents chart categories.

```csharp
public interface IChartCategory
```

## Members

| name | description |
| --- | --- |
| [AsCell](ascell) { get; set; } | Returns or sets IChartDataCell object. If category is multi-level then used IChartDataCell object for level "0". Read/write [`IChartDataCell`](../ichartdatacell). |
| [AsLiteral](asliteral) { get; set; } | Returns or sets AsLiteral if UseCell is false. Read/write Object. |
| [GroupingLevels](groupinglevels) { get; } | Managed container of the values of the chart category grouping levels. Multi-level category contain more then one grouping level. Grouping levels indexing is zero-based. Read-only [`IChartCategoryLevelsManager`](../ichartcategorylevelsmanager). |
| [UseCell](usecell) { get; } | If true then AsCell property is actual. In other words, worksheet is used for storing category (this case supports a multi-level category). If false then AsLiteral property is actual. In other words, worksheet is NOT used for storing category (and this case doesn't support a multi-level categories). Read-only Boolean. |
| [Value](value) { get; set; } | If UseCell is true then this property represents AsCell.Value property. If UseCell is false then this property represents AsLiteral property. Read/write Object. |
| [Remove](remove)() | Removes category from chart. |

### See Also

* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->