---
title: IPresentationSignedWarningInfo Class
type: docs
weight: 40
url: /python/aspose.slides.warnings/ipresentationsignedwarninginfo/
---

This warning indicates that the presentation being read has the signature <br/>            and this signature will be removed during processing.

**Namespace:** [aspose.slides.warnings](/python/aspose.slides.warnings/)

**Full Class Name:** aspose.slides.warnings.IPresentationSignedWarningInfo

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The IPresentationSignedWarningInfo type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|as_iwarning_info|Returns IWarningInfo interface.<br/>            Read-only [IWarningInfo](/python/aspose.slides.warnings/iwarninginfo/).|
|warning_type|Returns a type of warning.<br/>            Read-only [warning_type](/python/aspose.slides.warnings/iwarninginfo/).|
|description|Returns a human readable description of this warning.<br/>            Read-only string.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|send_warning(receiver)|If receiver is not null ends warning to a specified receiver and throws the <br/>            AbortRequestedException if receiver decided to abort a operation.|
