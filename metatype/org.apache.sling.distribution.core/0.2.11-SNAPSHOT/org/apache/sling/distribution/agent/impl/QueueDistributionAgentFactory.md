# Apache Sling Distribution Agent - Queue Agents Factory (`org.apache.sling.distribution.agent.impl.QueueDistributionAgentFactory`)

OSGi configuration factory for queueing agents

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Agent name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the agent. |
| title | Title | `true` | `String` | `null` | The display friendly title of the agent. |
| details | Details | `true` | `String` | `null` | The display friendly details of the agent. |
| enabled | Enabled | `true` | `Boolean` | `[true]` | Whether or not to start the distribution agent. |
| serviceName | Service Name | `true` | `String` | `null` | The name of the service used to access the repository. If not set, the calling user ResourceResolver will be used |
| log.level | Log Level | `true` | `String` | `[info]` | The log level recorded in the transient log accessible via http. |
| allowed.roots | Allowed roots | `true` | `String` | `null` | If set the agent will allow only distribution requests under the specified roots. |
| requestAuthorizationStrategy.target | Request Authorization Strategy | `true` | `String` | `[(name=default)]` | The target reference for the DistributionRequestAuthorizationStrategy used to authorize the access to distribution process,e.g. use target=(name=...) to bind to services by name. |
| packageBuilder.target | Package Builder | `true` | `String` | `[(name=default)]` | The target reference for the DistributionPackageBuilder used to create distribution packages, e.g. use target=(name=...) to bind to services by name. |
| triggers.target | Triggers | `true` | `String` | `[(name=)]` | The target reference for DistributionTrigger used to trigger distribution, e.g. use target=(name=...) to bind to services by name. |
| priorityQueues | Priority queues | `true` | `String` | `null` | List of priority queues that should used for specific paths.The selector format is  {queuePrefix}[|{mainQueueMatcher}]={pathMatcher}, e.g. french=/content/fr.* |
