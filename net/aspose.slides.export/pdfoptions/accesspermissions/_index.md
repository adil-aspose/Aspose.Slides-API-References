---
title: AccessPermissions
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 120
url: /net/aspose.slides.export/pdfoptions/accesspermissions/
---
## PdfOptions.AccessPermissions property

Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See [`PdfAccessPermissions`](../../pdfaccesspermissions).

```csharp
public PdfAccessPermissions AccessPermissions { get; set; }
```

## Examples

```csharp
[C#]
var pdfOptions = new PdfOptions();
pdfOptions.Password = "my_password";
pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;

using (var presentation = new Presentation())
{
    presentation.Save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
}
```

### See Also

* enum [PdfAccessPermissions](../../pdfaccesspermissions)
* class [PdfOptions](../../pdfoptions)
* namespace [Aspose.Slides.Export](../../pdfoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->