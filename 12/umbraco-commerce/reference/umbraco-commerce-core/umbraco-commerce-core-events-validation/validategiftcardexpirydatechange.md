---
title: ValidateGiftCardExpiryDateChange
description: API reference for ValidateGiftCardExpiryDateChange in Umbraco Commerce
---
## ValidateGiftCardExpiryDateChange

```csharp
public class ValidateGiftCardExpiryDateChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateGiftCardExpiryDateChange

```csharp
public ValidateGiftCardExpiryDateChange(GiftCardReadOnly giftCard, 
    ChangingValue<DateTime?> expiryDate)
```


### Properties

#### ExpiryDate

```csharp
public ChangingValue<DateTime?> ExpiryDate { get; }
```


---

#### GiftCard

```csharp
public GiftCardReadOnly GiftCard { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
