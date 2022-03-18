---
title: Presentation
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 80
url: /net/aspose.slides/presentation/presentation/
---
## Presentation constructor (1 of 6)

This constructor creates new presentation from scratch. Created presentation has one empty slide.

```csharp
public Presentation()
```

### See Also

* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Presentation constructor (2 of 6)

This constructor creates new presentation from scratch. Created presentation has one empty slide.

```csharp
public Presentation(LoadOptions loadOptions)
```

| parameter | description |
| --- | --- |
| loadOptions | Additional load options. |

### See Also

* class [LoadOptions](../../loadoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Presentation constructor (3 of 6)

This constructor is the primary mechanism for reading an existing Presentation.

```csharp
public Presentation(Stream stream)
```

| parameter | description |
| --- | --- |
| stream | Input stream. |

## Examples

```csharp
[C#]

FileStream fis = new FileStream("demo.pptx", FileMode.Open, FileAccess.Read);
Presentation pres = new Presentation(fis);
fis.Close();

[Visual Basic]

Dim fis As FileStream = New FileStream("demo.pptx", FileMode.Open, FileAccess.Read)
Dim pres As Presentation = New Presentation(fis)
fis.Close()
```

### See Also

* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Presentation constructor (4 of 6)

This constructor gets a source file path from which the contents of the Presentation are read.

```csharp
public Presentation(string file)
```

| parameter | description |
| --- | --- |
| file | Input file. |

## Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when input file has zero length |

## Examples

```csharp
[C#]

Presentation pres = new Presentation("demo.pptx");

[Visual Basic]

Dim pres As Presentation = New Presentation("demo.pptx")
```

### See Also

* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Presentation constructor (5 of 6)

This constructor is the primary mechanism for reading an existing Presentation.

```csharp
public Presentation(Stream stream, LoadOptions loadOptions)
```

| parameter | description |
| --- | --- |
| stream | Input stream. |
| loadOptions | Additional load options. |

### See Also

* class [LoadOptions](../../loadoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Presentation constructor (6 of 6)

This constructor gets a source file path from which the contents of the Presentation are read.

```csharp
public Presentation(string file, LoadOptions loadOptions)
```

| parameter | description |
| --- | --- |
| file | Input file. |
| loadOptions | Additional load options. |

## Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when input file has zero length |

### See Also

* class [LoadOptions](../../loadoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->