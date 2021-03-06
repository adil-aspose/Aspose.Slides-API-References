---
title: Nary
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 140
url: /net/aspose.slides.mathtext/mathelementbase/nary/
---
## MathElementBase.Nary method (1 of 2)

Creates a N-ary operator

```csharp
public IMathNaryOperator Nary(MathNaryOperatorTypes type, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| parameter | description |
| --- | --- |
| type | The N-ary operator type |
| lowerLimit | The lower limit |
| upperLimit | The upper limit |

## Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

## Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("i-1");
IMathElement lowerLimit = new MathematicalText("i=0");
IMathElement upperLimit = new MathematicalText("𝑛");
IMathNaryOperator naryOperator = baseElement.Nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathNaryOperatorTypes](../../mathnaryoperatortypes)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## MathElementBase.Nary method (2 of 2)

Creates a N-ary operator

```csharp
public IMathNaryOperator Nary(MathNaryOperatorTypes type, string lowerLimit, string upperLimit)
```

| parameter | description |
| --- | --- |
| type | The N-ary operator type |
| lowerLimit | The lower limit |
| upperLimit | The upper limit |

## Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

## Examples

Example:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("i").Nary(MathNaryOperatorTypes.Summation, "i=0", "𝑛");
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathNaryOperatorTypes](../../mathnaryoperatortypes)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
