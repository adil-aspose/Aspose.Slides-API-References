---
title: Chart
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 1140
url: /net/aspose.slides.charts/chart/
---
## Chart class

Represents an graphic chart on a slide.

```csharp
public class Chart : GraphicalObject, IChart
```

## Public Members

| name | description |
| --- | --- |
| [AsIFormattedTextContainer](asiformattedtextcontainer) { get; } | Allows to get base IFormattedTextContainer interface. Read-only [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](asithemeable) { get; } | Allows to get base IThemeable interface. Read-only [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](axes) { get; } | Provide access to chart axes. Read-only [`IAxesManager`](../iaxesmanager). |
| [BackWall](backwall) { get; } | Returns an object which allows to change format of the back wall of a 3D chart. Read-only [`IChartWall`](../ichartwall). |
| [ChartData](chartdata) { get; } | Returns information about the linked or embedded data associated with a chart. Read-only [`IChartData`](../ichartdata). |
| [ChartDataTable](chartdatatable) { get; } | Returns a data table of a chart. Read-only [`IDataTable`](../idatatable). |
| [ChartTitle](charttitle) { get; } | Returns or sets a chart title. Read-only [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](displayblanksas) { get; set; } | Returns or sets the way to plot blank cells on a chart. Read/write [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](floor) { get; } | Returns an object which allows to change format of the floor of a 3D chart. Read-only [`IChartWall`](../ichartwall). |
| [HasDataTable](hasdatatable) { get; set; } | Determines whether a chart has a data table. Read/write Boolean. |
| [HasLegend](haslegend) { get; set; } | Determines whether a chart has a legend. Read/write Boolean. |
| [HasRoundedCorners](hasroundedcorners) { get; set; } | Specifies the chart area shall have rounded corners. Read/write Boolean. |
| [HasTitle](hastitle) { get; set; } | Determines whether a chart has a visible title. Read/write Boolean. |
| [Legend](legend) { get; } | Returns or sets a legend for a chart. Read-only [`ILegend`](../ilegend). |
| [PlotArea](plotarea) { get; } | Represents the plot area of a chart. Read-only [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](plotvisiblecellsonly) { get; set; } | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write Boolean. |
| [Rotation3D](rotation3d) { get; } | Returns a 3D rotation of a chart. Read-only [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](showdatalabelsovermaximum) { get; set; } | Specifies data labels over the maximum of the chart shall be shown. Read/write Boolean. |
| [SideWall](sidewall) { get; } | Returns an object which allows to change format of the side wall of a 3D chart. Read-only [`IChartWall`](../ichartwall). |
| [Style](style) { get; set; } | Returns or sets the chart style. Read/write [`StyleType`](../styletype). |
| [TextFormat](textformat) { get; } | Returns chart text format. The property is not applicable for the following types: Treemap, Sunburst, Waterfall, Histogram, Funnel,BoxAndWhisker. Read-only [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](thememanager) { get; } | Returns theme manager. Read-only [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Type](type) { get; set; } | Returns or sets the chart type. Read/write [`ChartType`](../charttype). |
| [UserShapes](usershapes) { get; } | Specify the shapes drawn on top of the chart. Read-only [`IGroupShape`](../../aspose.slides/igroupshape). |
| [CreateThemeEffective](createthemeeffective)() | Returns an effective theme for this chart. |
| [ValidateChartLayout](validatechartlayout)() | Calculates actual values of chart elements. The actual values include position of elements that implement IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### See Also

* class [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [IChart](../ichart)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
