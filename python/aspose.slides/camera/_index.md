---
title: Camera Class
type: docs
weight: 190
url: /python/aspose.slides/camera/
---

Represents Camera.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.Camera

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The Camera type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|as_ipresentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/python/aspose.slides/ipresentationcomponent/).|
|camera_type|Camera type.<br/>            Read/write [CameraPresetType](/python/aspose.slides/camerapresettype/).|
|field_of_view_angle|Camera FOV (0-180 deg, field of View).<br/>            Read/write|
|zoom|Camera zoom (positive value in percentage).<br/>            Read/write|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/python/aspose.slides/ibaseslide/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/python/aspose.slides/ipresentation/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|set_rotation(latitude, longitude, revolution)|A rotation is defined through the use of a latitude<br/>            coordinate, a longitude coordinate, and a revolution about the axis <br/>            as the latitude and longitude coordinates.<br/>            If any of coordinate value is float.NaN, all rotation is undefined.|
|get_rotation()|A rotation is defined through the use of a latitude<br/>            coordinate, a longitude coordinate, and a revolution about the axis <br/>            as the latitude and longitude coordinates.<br/>            first element in return array - latitude, second - longitude, third - revolution.<br/>            Returns null if no rotation defined.|
