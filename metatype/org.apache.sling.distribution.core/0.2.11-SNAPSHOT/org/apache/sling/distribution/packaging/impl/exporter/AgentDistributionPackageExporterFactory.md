# Apache Sling Distribution Exporter - Agent Based Package Exporter (`org.apache.sling.distribution.packaging.impl.exporter.AgentDistributionPackageExporterFactory`)

Description for org.apache.sling.distribution.packaging.impl.exporter.AgentDistributionPackageExporterFactory

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Exporter name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the exporter. |
| queue | Queue | `true` | `String` | `null` | The name of the queue from which the packages should be exported. |
| drop.invalid.items | Drop invalid queue items | `true` | `String` | `[false]` | Remove invalid items from the queue. |
| agent.target | The target reference for the DistributionAgent that will be used to export packages. | `true` | `String` | `null` | Description for agent.target |
