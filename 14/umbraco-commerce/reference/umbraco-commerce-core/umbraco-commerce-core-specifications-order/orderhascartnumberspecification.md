---
title: OrderHasCartNumberSpecification
description: API reference for OrderHasCartNumberSpecification in Umbraco Commerce
---
## OrderHasCartNumberSpecification

```csharp
public class OrderHasCartNumberSpecification : IQuerySpecification<OrderReadOnly>, 
    ISpecification<OrderReadOnly>
```

**Inheritance**

* interface [IQuerySpecification&lt;!0&gt;](../../umbraco-commerce-common/umbraco-commerce-common-specifications/iqueryspecification-1.md)
* interface [ISpecification&lt;!0&gt;](../../umbraco-commerce-common/umbraco-commerce-common-specifications/ispecification-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Specifications.Order](README.md)

### Constructors

#### OrderHasCartNumberSpecification

```csharp
public OrderHasCartNumberSpecification(string cartNumber, StringComparisonType comparisonType)
```


### Properties

#### CartNumber

```csharp
public string CartNumber { get; }
```


---

#### ComparisonType

```csharp
public StringComparisonType ComparisonType { get; }
```


### Methods

#### Accept

```csharp
public void Accept(IVisitor visitor)
```


---

#### IsSatisfiedBy

```csharp
public bool IsSatisfiedBy(OrderReadOnly item)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
