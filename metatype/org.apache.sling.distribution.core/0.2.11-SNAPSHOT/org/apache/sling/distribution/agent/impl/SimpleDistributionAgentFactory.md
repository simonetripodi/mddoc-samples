# Apache Sling Distribution Agent - Simple Agents Factory (`org.apache.sling.distribution.agent.impl.SimpleDistributionAgentFactory`)

OSGi configuration factory for agents

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Agent name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the agent. |
| title | Title | `true` | `String` | `null` | The display friendly title of the agent. |
| details | Details | `true` | `String` | `null` | The display friendly details of the agent. |
| enabled | Enabled | `true` | `String` | `[true]` | Whether or not to start the distribution agent. |
| serviceName | Service Name | `true` | `String` | `null` | The name of the service used to access the repository. |
| log.level | Log Level | `true` | `String` | `[info]` | The log level recorded in the transient log accessible via http. |
| queue.processing.enabled | Queue Processing Enabled | `true` | `String` | `[true]` | Whether or not the distribution agent should process packages in the queues. |
| packageExporter.target | Exporter | `true` | `String` | `null` | The target reference for the DistributionPackageExporter used to receive (export) the distribution packages,e.g. use target=(name=...) to bind to services by name. |
| packageImporter.target | Importer | `true` | `String` | `null` | The target reference for the DistributionPackageImporter used to send (import) the distribution packages,e.g. use target=(name=...) to bind to services by name. |
| requestAuthorizationStrategy.target | Request Authorization Strategy | `true` | `String` | `null` | The target reference for the DistributionRequestAuthorizationStrategy used to authorize the access to distribution process,e.g. use target=(name=...) to bind to services by name. |
| triggers.target | Triggers | `true` | `String` | `[(name=)]` | The target reference for DistributionTrigger used to trigger distribution, e.g. use target=(name=...) to bind to services by name. |
