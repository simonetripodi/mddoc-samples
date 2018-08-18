# Apache Sling Distribution Request Authorization - Privilege Request Authorization Strategy

## `org.apache.sling.distribution.agent.impl.PrivilegeDistributionRequestAuthorizationStrategyFactory`

OSGi configuration for request based authorization strategy based on privileges

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Strategy name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | Description for name |
| jcrPrivilege | Jcr Privilege | `true` | `String` | `null` | Jcr privilege to check for authorizing distribution requests. The privilege is checked for the calling user session. |
