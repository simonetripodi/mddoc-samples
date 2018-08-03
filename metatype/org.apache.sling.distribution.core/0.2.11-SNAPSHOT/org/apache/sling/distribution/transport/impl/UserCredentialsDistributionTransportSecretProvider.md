# Apache Sling Distribution Transport Credentials - User Credentials based DistributionTransportSecretProvider (`org.apache.sling.distribution.transport.impl.UserCredentialsDistributionTransportSecretProvider`)

Description for org.apache.sling.distribution.transport.impl.UserCredentialsDistributionTransportSecretProvider

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Secret provider name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | Description for name |
| username | User Name | `true` | `String` | `null` | The name of the user used to perform remote actions. |
| password | Password | `true` | `String` | `null` | The clear text password to perform authentication. Warning: storing clear text passwords is not safe. |
