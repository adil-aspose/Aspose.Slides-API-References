---
title: IMotionEffect
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 430
url: /net/aspose.slides.animation/imotioneffect/
---
## IMotionEffect interface

Represent motion effect behavior of effect.

```csharp
public interface IMotionEffect : IBehavior
```

## Members

| name | description |
| --- | --- |
| [Angle](angle) { get; set; } | Describes the relative angle of the motion path. Read/write Single. |
| [AsIBehavior](asibehavior) { get; } | Allows to get base IBehavior interface. Read-only [`IBehavior`](../ibehavior). |
| [By](by) { get; set; } | Describes the relative offset value for the animation (in percents). Read/write PointF. |
| [From](from) { get; set; } | Specifies an x/y co-ordinate to start the animation from (in percents). Read/write PointF. |
| [Origin](origin) { get; set; } | Specifies what the origin of the motion path is relative to such as the layout of the slide, or the parent. Read/write [`MotionOriginType`](../motionorigintype). |
| [Path](path) { get; set; } | Specifies the path primitive followed by coordinates for the animation motion. Read/write [`IMotionPath`](../imotionpath). |
| [PathEditMode](patheditmode) { get; set; } | Specifies how the motion path moves when shape is moved. Read/write [`MotionPathEditMode`](../motionpatheditmode). |
| [RotationCenter](rotationcenter) { get; set; } | Describes the center of the rotation used to rotate a motion path by X angle. Read/write PointF. |
| [To](to) { get; set; } | Specifies the target location for an animation motion effect (in percents). Read/write PointF. |

### See Also

* interface [IBehavior](../ibehavior)
* namespace [Aspose.Slides.Animation](../../aspose.slides.animation)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->