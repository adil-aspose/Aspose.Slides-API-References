---
title: StreamWrapper
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 10180
url: /net/aspose.slides/streamwrapper/
---
## StreamWrapper class

Aspose.IO.Stream wrapper for COM interface.

```csharp
public class StreamWrapper : IStreamWrapper
```

## Public Members

| name | description |
| --- | --- |
| [AsIDisposable](asidisposable) { get; } | Allows to get base IDisposable interface. Read-only IDisposable. |
| [CanRead](canread) { get; } | Gets a value indicating whether the current stream supports reading. Read-only Boolean. |
| [CanSeek](canseek) { get; } | Gets a value indicating whether the current stream supports seeking. Read-only Boolean. |
| [CanWrite](canwrite) { get; } | Gets a value indicating whether the current stream supports writing. Read-only Boolean. |
| [Length](length) { get; } | Gets the length in bytes of the stream. Read-only Int64. |
| [Position](position) { get; } | Gets or sets the position within the current stream. Read-only Int64. |
| [Stream](stream) { get; } | Gets a stream. Read-only Stream. |
| [Close](close)() | Closes the current stream and releases any resources. |
| [Dispose](dispose)() | Disposes object. |
| [Flush](flush)() | Clears all buffers for this stream and causes any buffered data to be written to the underlying device. |
| [Read](read)(…) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| [ReadByte](readbyte)() | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| [Seek](seek)(…) | Sets the position within the current stream |
| [Write](write)(…) | writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| [WriteByte](writebyte)(…) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |

## Protected Members

| name | description |
| --- | --- |
| virtual [Dispose](dispose)(…) | Disposes object. |

### See Also

* interface [IStreamWrapper](../istreamwrapper)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
