<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-core-server](./kibana-plugin-core-server.md) &gt; [CoreSetup](./kibana-plugin-core-server.coresetup.md)

## CoreSetup interface

Context passed to the plugins `setup` method.

<b>Signature:</b>

```typescript
export interface CoreSetup<TPluginsStart extends object = object, TStart = unknown> 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [capabilities](./kibana-plugin-core-server.coresetup.capabilities.md) | <code>CapabilitiesSetup</code> | [CapabilitiesSetup](./kibana-plugin-core-server.capabilitiessetup.md) |
|  [context](./kibana-plugin-core-server.coresetup.context.md) | <code>ContextSetup</code> | [ContextSetup](./kibana-plugin-core-server.contextsetup.md) |
|  [elasticsearch](./kibana-plugin-core-server.coresetup.elasticsearch.md) | <code>ElasticsearchServiceSetup</code> | [ElasticsearchServiceSetup](./kibana-plugin-core-server.elasticsearchservicesetup.md) |
|  [getStartServices](./kibana-plugin-core-server.coresetup.getstartservices.md) | <code>StartServicesAccessor&lt;TPluginsStart, TStart&gt;</code> | [StartServicesAccessor](./kibana-plugin-core-server.startservicesaccessor.md) |
|  [http](./kibana-plugin-core-server.coresetup.http.md) | <code>HttpServiceSetup</code> | [HttpServiceSetup](./kibana-plugin-core-server.httpservicesetup.md) |
|  [metrics](./kibana-plugin-core-server.coresetup.metrics.md) | <code>MetricsServiceSetup</code> | [MetricsServiceSetup](./kibana-plugin-core-server.metricsservicesetup.md) |
|  [savedObjects](./kibana-plugin-core-server.coresetup.savedobjects.md) | <code>SavedObjectsServiceSetup</code> | [SavedObjectsServiceSetup](./kibana-plugin-core-server.savedobjectsservicesetup.md) |
|  [uiSettings](./kibana-plugin-core-server.coresetup.uisettings.md) | <code>UiSettingsServiceSetup</code> | [UiSettingsServiceSetup](./kibana-plugin-core-server.uisettingsservicesetup.md) |
|  [uuid](./kibana-plugin-core-server.coresetup.uuid.md) | <code>UuidServiceSetup</code> | [UuidServiceSetup](./kibana-plugin-core-server.uuidservicesetup.md) |

