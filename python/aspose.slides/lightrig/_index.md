---
title: LightRig Class
type: docs
weight: 2980
url: /python/aspose.slides/lightrig/
---

Represents LightRig.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.LightRig

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The LightRig type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|as_ipresentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/python/aspose.slides/ipresentationcomponent/).|
|direction|Light direction.<br/>            Read/write [LightingDirection](/python/aspose.slides/lightingdirection/).|
|light_type|Represents a preset light right that can be applied to a shape. <br/>            The light rig represents a group of lights oriented<br/>            in a specific way relative to a 3D scene.<br/>            Read/write [LightRigPresetType](/python/aspose.slides/lightrigpresettype/).|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/python/aspose.slides/ibaseslide/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/python/aspose.slides/ipresentation/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|set_rotation(latitude, longitude, revolution)|A rotation is defined through the use of a latitude<br/>            coordinate, a longitude coordinate, and a revolution about the axis <br/>            as the latitude and longitude coordinates.<br/>            If any of coordinate value is float.NaN, all rotation is undefined.|
|get_rotation()|A rotation is defined through the use of a latitude<br/>            coordinate, a longitude coordinate, and a revolution about the axis <br/>            as the latitude and longitude coordinates.<br/>            first element in return array - latitude, second - longitude, third - revolution.<br/>            Returns null if no rotation defined.|
