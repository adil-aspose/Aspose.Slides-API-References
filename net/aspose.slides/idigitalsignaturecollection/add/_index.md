---
title: Add
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.slides/idigitalsignaturecollection/add/
---
## IDigitalSignatureCollection.Add method

Adds the signature at the end of collection.

```csharp
public void Add(IDigitalSignature digitalSignature)
```

| parameter | description |
| --- | --- |
| digitalSignature | Signature to add. |

## Examples

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    DigitalSignature signature = new DigitalSignature("testsignature1.pfx", @"testpass1");
    signature.Comments = "Aspose.Slides digital signing test.";
    pres.DigitalSignatures.Add(signature);
    pres.Save("SomePresentationSigned.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IDigitalSignature](../../idigitalsignature)
* interface [IDigitalSignatureCollection](../../idigitalsignaturecollection)
* namespace [Aspose.Slides](../../idigitalsignaturecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->