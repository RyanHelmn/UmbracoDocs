---
title: ExportTemplateNotificationEventBase<TEntity>
description: API reference for ExportTemplateNotificationEventBase<TEntity> in Umbraco Commerce
---
## ExportTemplateNotificationEventBase&lt;TEntity&gt;

```csharp
public abstract class ExportTemplateNotificationEventBase<TEntity> : NotificationEventBase
    where TEntity : ExportTemplateReadOnly
```

**Inheritance**

* class [NotificationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/notificationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Notification](README.md)

### Constructors

#### ExportTemplateNotificationEventBase&lt;TEntity&gt;

```csharp
public ExportTemplateNotificationEventBase(TEntity exportTemplate)
```


### Properties

#### ExportTemplate

```csharp
public TEntity ExportTemplate { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
