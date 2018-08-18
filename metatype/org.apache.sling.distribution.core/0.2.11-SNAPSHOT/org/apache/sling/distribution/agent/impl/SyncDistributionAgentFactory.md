# Apache Sling Distribution Agent - Sync Agents Factory

## `org.apache.sling.distribution.agent.impl.SyncDistributionAgentFactory`

OSGi configuration factory for syncing agents

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Agent name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the agent. |
| title | Title | `true` | `String` | `null` | The display friendly title of the agent. |
| details | Details | `true` | `String` | `null` | The display friendly details of the agent. |
| enabled | Enabled | `true` | `Boolean` | `[true]` | Whether or not to start the distribution agent. |
| serviceName | Service Name | `true` | `String` | `null` | The name of the service used to access the repository. If not set, the calling user ResourceResolver will be used |
| log.level | Log Level | `true` | `String` | `[info]` | The log level recorded in the transient log accessible via http. |
| queue.processing.enabled | Queue Processing Enabled | `true` | `Boolean` | `[true]` | Whether or not the distribution agent should process packages in the queues. |
| passiveQueues | Passive queues | `true` | `String` | `null` | List of queues that should be disabled.These queues will gather all the packages until they are removed explicitly. |
| packageExporter.endpoints | Exporter Endpoints | `true` | `String` | `null` | List of endpoints from which packages are received (exported) |
| packageImporter.endpoints | Importer Endpoints | `true` | `String` | `null` | List of endpoints to which packages are sent (imported). The list can be given as a map in case a queue should be configured for each endpoint, e.g. queueName=http://... |
| retry.strategy | Retry Strategy | `true` | `String` | `[none]` | The strategy to apply after a certain number of failed retries. |
| retry.attempts | Retry attempts | `true` | `Integer` | `[100]` | The number of times to retry until the retry strategy is applied. |
| pull.items | Pull Items | `true` | `Integer` | `[100]` | Number of subsequent pull requests to make. |
| http.conn.timeout | HTTP connection timeout | `true` | `Integer` | `[10]` | The connection timeout for HTTP requests (in seconds). |
| requestAuthorizationStrategy.target | Request Authorization Strategy | `true` | `String` | `[(name=default)]` | The target reference for the DistributionRequestAuthorizationStrategy used to authorize the access to distribution process,e.g. use target=(name=...) to bind to services by name. |
| transportSecretProvider.target | Transport Secret Provider | `true` | `String` | `[(name=default)]` | The target reference for the DistributionTransportSecretProvider used to obtain the credentials used for accessing the remote endpoints, e.g. use target=(name=...) to bind to services by name. |
| packageBuilder.target | Package Builder | `true` | `String` | `[(name=default)]` | The target reference for the DistributionPackageBuilder used to create distribution packages, e.g. use target=(name=...) to bind to services by name. |
| triggers.target | Triggers | `true` | `String` | `[(name=)]` | The target reference for DistributionTrigger used to trigger distribution, e.g. use target=(name=...) to bind to services by name. |
