---
title: Function
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 50
url: /net/aspose.slides.mathtext/imathelement/function/
---
## IMathElement.Function method (1 of 2)

Takes a function of an argument using this instance as the function name

```csharp
public IMathFunction Function(IMathElement functionArgument)
```

| parameter | description |
| --- | --- |
| functionArgument | An argument of the function |

## Return Value

New math element of type [`IMathFunction`](../../imathfunction)

## Examples

Example:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionName.Function(functionArg);
```

### See Also

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## IMathElement.Function method (2 of 2)

Takes a function of an argument using this instance as the function name

```csharp
public IMathFunction Function(string functionArgument)
```

| parameter | description |
| --- | --- |
| functionArgument | An argument of the function |

## Return Value

New math element of type [`IMathFunction`](../../imathfunction)

## Examples

Example:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathFunction func = functionName.Function("x");
```

### See Also

* interface [IMathFunction](../../imathfunction)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->