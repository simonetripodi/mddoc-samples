# Apache Sling Distribution Trigger - Persisted Jcr Event Triggers Factory (`org.apache.sling.distribution.trigger.impl.PersistedJcrEventDistributionTriggerFactory`)

Description for org.apache.sling.distribution.trigger.impl.PersistedJcrEventDistributionTriggerFactory

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Trigger name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the trigger. |
| path | Path | `true` | `String` | `null` | The path for which changes are listened and distributed as persisted nugget events. |
| serviceName | Service Name | `true` | `String` | `null` | The service used to listen for jcr events |
| nuggetsPath | Nuggets Path | `true` | `String` | `[/var/sling/distribution/nuggets]` | The location where serialization of jcr events will be stored |
