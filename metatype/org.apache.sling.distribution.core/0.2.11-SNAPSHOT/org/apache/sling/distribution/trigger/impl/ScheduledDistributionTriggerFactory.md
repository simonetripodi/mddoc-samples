# Apache Sling Distribution Trigger - Scheduled Triggers Factory

## `org.apache.sling.distribution.trigger.impl.ScheduledDistributionTriggerFactory`

Triggers a distribution request of the given type (action) for the given path (path) at a periodical time interval (seconds).

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Trigger name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the trigger. |
| action | Distribution Type | `true` | `String` | `null` | The type of the distribution request produced by this trigger in ('ADD', 'DELETE', 'PULL', 'TEST'). Default 'PULL'. |
| path | Distributed Path | `true` | `String` | `null` | The path to be distributed periodically. |
| seconds | Interval in Seconds | `true` | `String` | `null` | The number of seconds between distribution requests. Default 30 seconds. |
| serviceName | Service Name | `true` | `String` | `null` | The name of the service used to trigger the distribution requests. |
