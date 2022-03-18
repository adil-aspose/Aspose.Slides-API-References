---
title: ThreeDFormat
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 140
url: /net/aspose.slides/itextframeformat/threedformat/
---
## ITextFrameFormat.ThreeDFormat property

Returns the ThreeDFormat object that represents 3d effect properties for a text. Read-only [`IThreeDFormat`](../../ithreedformat).

```csharp
public IThreeDFormat ThreeDFormat { get; }
```

## Examples

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAutoShape autoShape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);

    ITextFrame textFrame = autoShape.TextFrame;

    textFrame.Text = "Aspose.Slide Test Text";

    // Set text transformation
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUpPour;

    // Set Extrusion
    textFrame.TextFrameFormat.ThreeDFormat.ExtrusionColor.Color = Color.Orange;
    textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 6;

    // Set Contour
    textFrame.TextFrameFormat.ThreeDFormat.ContourColor.Color = Color.DarkRed;
    textFrame.TextFrameFormat.ThreeDFormat.ContourWidth = 1.5;

    // Set Depth
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;

    // Set Material
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;

    // Set Lighting
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);

    // Set camera type
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
}
```

### See Also

* interface [IThreeDFormat](../../ithreedformat)
* interface [ITextFrameFormat](../../itextframeformat)
* namespace [Aspose.Slides](../../itextframeformat)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->