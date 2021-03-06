---
title: IStringChartValue
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 2100
url: /net/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue interface

Represent string value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value.

```csharp
public interface IStringChartValue : IMultipleCellChartValue
```

## Members

| name | description |
| --- | --- |
| [AsIMultipleCellChartValue](asimultiplecellchartvalue) { get; } | Allows to get base IMultipleCellChartValue interface. Read-only [`IMultipleCellChartValue`](../imultiplecellchartvalue). |
| [AsLiteralString](asliteralstring) { get; set; } | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. Read/write String. |
| [GetCellsAddressInWorkbook](getcellsaddressinworkbook)() | If DataSourceType property is DataSourceType.Worksheet then this method returns address of the cells in workbook which represent the string data. Otherwise return empty string. |
| [SetFromOneCell](setfromonecell)(…) | Sets value from specified cell. |
| [ToString](tostring)() | Returns string representation. |

### See Also

* interface [IMultipleCellChartValue](../imultiplecellchartvalue)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
