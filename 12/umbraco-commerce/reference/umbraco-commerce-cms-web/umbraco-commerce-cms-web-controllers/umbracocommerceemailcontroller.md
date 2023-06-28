---
title: UmbracoCommerceEmailController
description: API reference for UmbracoCommerceEmailController in Umbraco Commerce
---
## UmbracoCommerceEmailController

```csharp
public class UmbracoCommerceEmailController : UmbracoCommerceAuthorizedJsonControllerBase
```

**Inheritance**

* class [UmbracoCommerceAuthorizedJsonControllerBase](umbracocommerceauthorizedjsoncontrollerbase.md)

**Namespace**
* [Umbraco.Commerce.Cms.Web.Controllers](README.md)

### Constructors

#### UmbracoCommerceEmailController

```csharp
public UmbracoCommerceEmailController(IBackOfficeSecurityAccessor backOfficeSecurityAccesor, 
    UmbracoCommerceContext ctx)
```


### Methods

#### SendDiscountEmail

```csharp
public IActionResult SendDiscountEmail(SendDiscountEmailDto dto)
```


---

#### SendGiftCardEmail

```csharp
public IActionResult SendGiftCardEmail(SendGiftCardEmailDto dto)
```


---

#### SendOrderEmail

```csharp
public IActionResult SendOrderEmail(SendOrderEmailDto dto)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.Web.dll -->