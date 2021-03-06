---
title: GeometryShape
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 4760
url: /net/aspose.slides/geometryshape/
---
## GeometryShape class

Represents the parent class for all geometric shapes.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## Public Members

| name | description |
| --- | --- |
| [Adjustments](adjustments) { get; } | Returns a collection of shape's adjustment values. Read-only [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [ShapeStyle](shapestyle) { get; } | Returns shape's style object. Read-only [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](shapetype) { get; set; } | Returns or sets the geometry preset type. Note: on value changing all adjustment values will reset to their default values. Read/write [`ShapeType`](../shapetype). |
| [CreateShapeElements](createshapeelements)() | Creates and returns array of shape's elements. |
| [GetGeometryPaths](getgeometrypaths)() | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [SetGeometryPath](setgeometrypath)(…) | Updates shape geometry from [`IGeometryPath`](../igeometrypath) object. Coordinates must be relative to the left top corner of the shape. Changes the type of the shape ([`ShapeType`](./shapetype)) to Custom. |
| [SetGeometryPaths](setgeometrypaths)(…) | Updates shape geometry from array of [`IGeometryPath`](../igeometrypath). Coordinates must be relative to the left top corner of the shape. Changes the type of the shape ([`ShapeType`](./shapetype)) to Custom. |

### See Also

* class [Shape](../shape)
* interface [IGeometryShape](../igeometryshape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
