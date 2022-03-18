---
title: Add
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection.Add method (1 of 4)

Creates new chart series and adds it to the collection.

```csharp
public IChartSeries Add(ChartType type)
```

| parameter | description |
| --- | --- |
| type | Type of series |

## Return Value

New chart series.

### See Also

* interface [IChartSeries](../../ichartseries)
* enum [ChartType](../../charttype)
* interface [IChartSeriesCollection](../../ichartseriescollection)
* namespace [Aspose.Slides.Charts](../../ichartseriescollection)
* assembly [Aspose.Slides](../../../)

---

## IChartSeriesCollection.Add method (2 of 4)

Creates new chart series from [`IChartCellCollection`](../../ichartcellcollection) and adds it to the collection.

```csharp
public IChartSeries Add(IChartCellCollection cellsWithSeriesName, ChartType type)
```

| parameter | description |
| --- | --- |
| cellsWithSeriesName | Cells which contain series name. |
| type | Type set type of series |

## Return Value

Added chart series or series that already is in collection.

## Remarks

If chart series careted from same cell already in collection then method adds nothing and returns it's index.

### See Also

* interface [IChartSeries](../../ichartseries)
* interface [IChartCellCollection](../../ichartcellcollection)
* enum [ChartType](../../charttype)
* interface [IChartSeriesCollection](../../ichartseriescollection)
* namespace [Aspose.Slides.Charts](../../ichartseriescollection)
* assembly [Aspose.Slides](../../../)

---

## IChartSeriesCollection.Add method (3 of 4)

Creates new chart series from [`IChartDataCell`](../../ichartdatacell) and adds it to the collection.

```csharp
public IChartSeries Add(IChartDataCell cellWithSeriesName, ChartType type)
```

| parameter | description |
| --- | --- |
| cellWithSeriesName | Cell which contain series name. |
| type | Type set type of series |

## Return Value

Added chart series or series that already is in collection.

## Remarks

If chart series careted from same cell already in collection then method adds nothing and returns it's index.

### See Also

* interface [IChartSeries](../../ichartseries)
* interface [IChartDataCell](../../ichartdatacell)
* enum [ChartType](../../charttype)
* interface [IChartSeriesCollection](../../ichartseriescollection)
* namespace [Aspose.Slides.Charts](../../ichartseriescollection)
* assembly [Aspose.Slides](../../../)

---

## IChartSeriesCollection.Add method (4 of 4)

Creates new chart series from value and adds it to the collection.

```csharp
public IChartSeries Add(string name, ChartType type)
```

| parameter | description |
| --- | --- |
| name | Series name. |
| type | Type set type of series |

## Return Value

Added chart series.

### See Also

* interface [IChartSeries](../../ichartseries)
* enum [ChartType](../../charttype)
* interface [IChartSeriesCollection](../../ichartseriescollection)
* namespace [Aspose.Slides.Charts](../../ichartseriescollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->