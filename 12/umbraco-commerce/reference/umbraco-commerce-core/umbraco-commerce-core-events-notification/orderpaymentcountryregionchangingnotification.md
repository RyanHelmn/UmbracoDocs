---
title: OrderPaymentCountryRegionChangingNotification
description: API reference for OrderPaymentCountryRegionChangingNotification in Umbraco Commerce
---
## OrderPaymentCountryRegionChangingNotification

```csharp
public class OrderPaymentCountryRegionChangingNotification : 
    OrderPaymentCountryRegionChangeNotificationBase<Order>
```

**Inheritance**

* class [OrderPaymentCountryRegionChangeNotificationBase&lt;TEntity&gt;](orderpaymentcountryregionchangenotificationbase-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Notification](README.md)

### Constructors

#### OrderPaymentCountryRegionChangingNotification

```csharp
public OrderPaymentCountryRegionChangingNotification(Order order, ChangingValue<Guid?> countryId, 
    ChangingValue<Guid?> regionId)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
