---
title: ValidateRegionCodeChange
description: API reference for ValidateRegionCodeChange in Umbraco Commerce
---
## ValidateRegionCodeChange

```csharp
public class ValidateRegionCodeChange : ValidationEventBase
```

**Inheritance**

* Class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateRegionCodeChange

```csharp
public ValidateRegionCodeChange(RegionReadOnly region, ChangingValue<string> code)
```


### Properties

#### Code

```csharp
public ChangingValue<string> Code { get; }
```


---

#### Region

```csharp
public RegionReadOnly Region { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->