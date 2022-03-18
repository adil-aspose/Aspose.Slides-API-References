---
title: IMathFraction
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 7780
url: /net/aspose.slides.mathtext/imathfraction/
---
## IMathFraction interface

Specifies the fraction object, consisting of a numerator and denominator separated by a fraction bar. The fraction bar can be horizontal or diagonal, depending on the fraction properties. The fraction object is also used to represent the stack function, which places one element above another, with no fraction bar.

```csharp
public interface IMathFraction : IMathElement
```

## Members

| name | description |
| --- | --- |
| [AsIMathElement](asimathelement) { get; } | Allows to get base IMathElement interface [`IMathElement`](../imathelement) |
| [Denominator](denominator) { get; } | Denominator |
| [FractionType](fractiontype) { get; set; } | Fraction type Default: Bar |
| [Numerator](numerator) { get; } | Numerator |

## Examples

Example:

```csharp
[C#]
IMathFraction mathFraction = new MathematicalText("x").Divide("y");
IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```

### See Also

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->