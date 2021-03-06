---
title: LoadingStreamBehavior Enumeration
type: docs
weight: 9730
url: /python/aspose.slides/loadingstreambehavior/
---

The stream passed to a method is considered as a Binary Large Object (BLOB) (see <br/>            [IBlobManagementOptions](/python/aspose.slides/iblobmanagementoptions/) description). Values of this enumeration identify how <br/>            the stream should be treated when it passed to the method. Depending on the <br/>            requirements, different decisions could be made to provide the most efficient behavior.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Name:** aspose.slides.LoadingStreamBehavior

**Assembly:**  Aspose.Slides Version: 22.1.0.0

## **Members**
|**Member name**|**Description**|
| :- | :- |
|READ_STREAM_AND_RELEASE|The stream will be read to the end and then released - i.e. it will be guaranteed that this stream <br/>            will not be used by [IPresentation](/python/aspose.slides/ipresentation/) instance in the future. It can be closed by the client <br/>            code or used in any other way.|
|KEEP_LOCKED|The stream will be locked inside the [IPresentation](/python/aspose.slides/ipresentation/) object, i.e. the ownership of <br/>            the stream will be transferred. The [IPresentation](/python/aspose.slides/ipresentation/) object will be responsible to <br/>            correctly dispose the stream when this object will be disposed itself. <br/>            This behavior is extremely useful when you need to serialize a large BLOB file (such as a large <br/>            video or audio -see [IBlobManagementOptions](/python/aspose.slides/iblobmanagementoptions/) description) and want to prevent loading <br/>            this file into memory or other performance issues. You may just open the stream <br/>            for this file and pass to a method, choosing [KEEP_LOCKED](/python/aspose.slides/loadingstreambehavior/) LoadingStreamBehavior.|
