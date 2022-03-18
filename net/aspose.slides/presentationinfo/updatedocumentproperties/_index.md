---
title: UpdateDocumentProperties
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 40
url: /net/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo.UpdateDocumentProperties method

Updates properties of binded presentation.

```csharp
public void UpdateDocumentProperties(IDocumentProperties documentProperties)
```

## Examples

This sample shows how to call the `UpdateDocumentProperties` method to update the document properties returned by call of the [`ReadDocumentProperties`](../readdocumentproperties) method.

```csharp
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo("pres.pptx");
IDocumentProperties props = info.ReadDocumentProperties();
props.Subject = "New subject";
props.LastSavedTime = DateTime.UtcNow;
info.UpdateDocumentProperties(props);
info.WriteBindedPresentation("new_pres.pptx");
```

### See Also

* interface [IDocumentProperties](../../idocumentproperties)
* class [PresentationInfo](../../presentationinfo)
* namespace [Aspose.Slides](../../presentationinfo)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->