# Apache Sling Distribution Trigger - Jcr Event Triggers Factory (`org.apache.sling.distribution.trigger.impl.JcrEventDistributionTriggerFactory`)

Triggers a distribution request ('ADD', 'DELETE') for the given path (path) whenever the JCR node at the given path is modified (added, resp. removed).

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Trigger name: {name} on path {path}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the trigger. |
| path | Path | `true` | `String` | `null` | The path for which changes are distributed. |
| ignoredPathsPatterns | Ignored Paths Patterns | `true` | `String` | `null` | The paths matching one of these patterns will be ignored. |
| serviceName | Service Name | `true` | `String` | `null` | The service used to listen for jcr events |
| deep | Use deep distribution | `true` | `Boolean` | `[false]` | Distribute entire subtree of the event node path. Default is 'false'. |
