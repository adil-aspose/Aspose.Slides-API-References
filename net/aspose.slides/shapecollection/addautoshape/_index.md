---
title: AddAutoShape
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 280
url: /net/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection.AddAutoShape method (1 of 2)

Creates a new AutoShape, tunes it from default template and adds it to the end of the collection.

```csharp
public IAutoShape AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)
```

| parameter | description |
| --- | --- |
| shapeType | The [`ShapeType`](../../shapetype) of shape. |
| x | The X-coordinate for a left side of shape's frame. |
| y | The Y-coordinate for a top side of shape's frame. |
| width | The width of shape's frame. |
| height | The height of shape's frame. |

## Return Value

Created AutoShape object.

### See Also

* interface [IAutoShape](../../iautoshape)
* enum [ShapeType](../../shapetype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## ShapeCollection.AddAutoShape method (2 of 2)

Creates a new AutoShape and adds it to the end of the collection.

```csharp
public IAutoShape AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, 
    bool createFromTemplate)
```

| parameter | description |
| --- | --- |
| shapeType | The [`ShapeType`](../../shapetype) of shape. |
| x | The X-coordinate for a left side of shape's frame. |
| y | The Y-coordinate for a top side of shape's frame. |
| width | The width of shape's frame. |
| height | The height of shape's frame. |
| createFromTemplate | If true then new shape will be tuned from default template. Not empty name, simple style, text centered will be assined to the new shape. If false then all values of the properties of the new shape will have default values. |

## Return Value

Created AutoShape object.

### See Also

* interface [IAutoShape](../../iautoshape)
* enum [ShapeType](../../shapetype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->