---
title: Connector
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 2540
url: /net/aspose.slides/connector/
---
## Connector class

Represents a connector.

```csharp
public class Connector : GeometryShape, IConnector
```

## Public Members

| name | description |
| --- | --- |
| [ConnectorLock](connectorlock) { get; } | Returns connector's locks. Read-only [`IConnectorLock`](../iconnectorlock). |
| [EndShapeConnectedTo](endshapeconnectedto) { get; set; } | Returns or sets the shape to attach the end of the connector to. Read/write [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](endshapeconnectionsiteindex) { get; set; } | Returns or sets the index of connection site for end shape. Read/write UInt32. |
| [ShapeLock](shapelock) { get; } | Returns shape's locks. Read-only [`IConnectorLock`](../iconnectorlock). |
| override [ShapeType](shapetype) { get; set; } | Returns or sets the AutoShape type. Read/write [`ShapeType`](../shapetype). |
| [StartShapeConnectedTo](startshapeconnectedto) { get; set; } | Returns or sets the shape to attach the beginning of the connector to. Read/write [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](startshapeconnectionsiteindex) { get; set; } | Returns or sets the index of connection site for start shape. Read/write UInt32. |
| [Reroute](reroute)() | Reroutes connector so that it take the shortest possible path between the shapes it connect. |

### See Also

* class [GeometryShape](../geometryshape)
* interface [IConnector](../iconnector)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
