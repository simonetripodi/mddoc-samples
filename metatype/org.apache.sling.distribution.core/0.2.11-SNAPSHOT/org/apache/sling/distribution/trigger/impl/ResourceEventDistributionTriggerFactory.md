# Apache Sling Distribution Trigger - Resource Event Triggers Factory (`org.apache.sling.distribution.trigger.impl.ResourceEventDistributionTriggerFactory`)

Triggers a distribution request ('ADD', 'DELETE') for the given path (path) whenever the resource at the given path is modified (added, resp. removed).

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Trigger name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the trigger. |
| path | Path | `true` | `String` | `null` | The resource path for which changes are distributed |
