---
title: ILineFormat
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 6000
url: /net/aspose.slides/ilineformat/
---
## ILineFormat interface

Represents format of a line.

```csharp
public interface ILineFormat : ILineParamSource
```

## Members

| name | description |
| --- | --- |
| [Alignment](alignment) { get; set; } | Returns or sets the line alignment. Read/write [`LineAlignment`](../linealignment). |
| [AsILineParamSource](asilineparamsource) { get; } | Allows to get base ILineParamSource interface. Read-only [`ILineParamSource`](../ilineparamsource). |
| [BeginArrowheadLength](beginarrowheadlength) { get; set; } | Returns or sets the arrowhead length at the beginning of a line. Read/write [`LineArrowheadLength`](../linearrowheadlength). |
| [BeginArrowheadStyle](beginarrowheadstyle) { get; set; } | Returns or sets the arrowhead style at the beginning of a line. Read/write [`LineArrowheadStyle`](../linearrowheadstyle). |
| [BeginArrowheadWidth](beginarrowheadwidth) { get; set; } | Returns or sets the arrowhead width at the beginning of a line. Read/write [`LineArrowheadWidth`](../linearrowheadwidth). |
| [CapStyle](capstyle) { get; set; } | Returns or sets the line cap style. Read/write [`LineCapStyle`](../linecapstyle). |
| [CustomDashPattern](customdashpattern) { get; set; } | Returns or sets the custom dash pattern. Read/write Single[]. |
| [DashStyle](dashstyle) { get; set; } | Returns or sets the line dash style. Read/write [`LineDashStyle`](../linedashstyle). |
| [EndArrowheadLength](endarrowheadlength) { get; set; } | Returns or sets the arrowhead length at the end of a line. Read/write [`LineArrowheadLength`](../linearrowheadlength). |
| [EndArrowheadStyle](endarrowheadstyle) { get; set; } | Returns or sets the arrowhead style at the end of a line. Read/write [`LineArrowheadStyle`](../linearrowheadstyle). |
| [EndArrowheadWidth](endarrowheadwidth) { get; set; } | Returns or sets the arrowhead width at the end of a line. Read/write [`LineArrowheadWidth`](../linearrowheadwidth). |
| [FillFormat](fillformat) { get; } | Returns the fill format of a line. Read-only [`ILineFillFormat`](../ilinefillformat). |
| [IsFormatNotDefined](isformatnotdefined) { get; } | Returns true if line format is not defined (as just created, default). Read-only Boolean. |
| [JoinStyle](joinstyle) { get; set; } | Returns or sets the lines join style. Read/write [`LineJoinStyle`](../linejoinstyle). |
| [MiterLimit](miterlimit) { get; set; } | Returns or sets the miter limit of a line. Read/write Single. |
| [SketchFormat](sketchformat) { get; } | Returns the sketch format of a line. Read-only [`ISketchFormat`](../isketchformat). |
| [Style](style) { get; set; } | Returns or sets the line style. Read/write [`LineStyle`](../linestyle). |
| [Width](width) { get; set; } | Returns or sets the width of a line. Read/write Double. |
| [Equals](equals)(…) | Determines whether the two LineFormat instances are equal. |
| [GetEffective](geteffective)() | Gets effective line formatting data with the inheritance applied. |

### See Also

* interface [ILineParamSource](../ilineparamsource)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->