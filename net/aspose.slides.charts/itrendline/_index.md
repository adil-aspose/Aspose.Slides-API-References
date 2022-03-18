---
title: ITrendline
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 2120
url: /net/aspose.slides.charts/itrendline/
---
## ITrendline interface

Class represents trend line of chart series

```csharp
public interface ITrendline : IOverridableText
```

## Members

| name | description |
| --- | --- |
| [AsIOverridableText](asioverridabletext) { get; } | Returns IOverridableText interface. Read-only [`IOverridableText`](../ioverridabletext). |
| [Backward](backward) { get; set; } | Specifies the number of categories (or units on a scatter chart) that the trend line extends before the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative value. Read/write Double. |
| [DisplayEquation](displayequation) { get; set; } | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue). Read/write Boolean. |
| [DisplayRSquaredValue](displayrsquaredvalue) { get; set; } | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation). Read/write Boolean. |
| [Format](format) { get; set; } | Represents the format of the trend line. Read/write [`IFormat`](../iformat). |
| [Forward](forward) { get; set; } | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative value. Read/write Double. |
| [Intercept](intercept) { get; set; } | Specifies the value where the trendline shall cross the y axis. This property shall be supported only when the trendline type is exp, linear, or poly. Read/write Double. |
| [Order](order) { get; set; } | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6. Read/write Byte. |
| [Period](period) { get; set; } | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend line variants. Value must be between 2 and 255. Read/write Byte. |
| [RelatedLegendEntry](relatedlegendentry) { get; } | Represents legend entry related with this trendline Read-only [`ILegendEntryProperties`](../ilegendentryproperties). |
| [TrendlineName](trendlinename) { get; set; } | Gets or sets name of the trendline. Read/write String. |
| [TrendlineType](trendlinetype) { get; set; } | Gets or sets type of trend line. Read/write [`TrendlineType`](./trendlinetype). |

### See Also

* interface [IOverridableText](../ioverridabletext)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->