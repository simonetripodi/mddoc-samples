# Apache Sling Distribution Importer - Remote Package Importer Factory

## `org.apache.sling.distribution.packaging.impl.importer.RemoteDistributionPackageImporterFactory`

Description for org.apache.sling.distribution.packaging.impl.importer.RemoteDistributionPackageImporterFactory

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Importer name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the importer. |
| endpoints | Endpoints | `true` | `String` | `null` | The list of endpoints to which the packages will be imported. |
| transportSecretProvider.target | Transport Secret Provider | `true` | `String` | `null` | The target reference for the DistributionTransportSecretProvider used to obtain the credentials used for accessing the remote endpoints, e.g. use target=(name=...) to bind to services by name. |
