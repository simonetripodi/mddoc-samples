# Apache Sling Distribution Exporter - Remote Package Exporter Factory (`org.apache.sling.distribution.packaging.impl.exporter.RemoteDistributionPackageExporterFactory`)

Description for org.apache.sling.distribution.packaging.impl.exporter.RemoteDistributionPackageExporterFactory

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Exporter name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the exporter. |
| endpoints | Endpoints | `true` | `String` | `null` | The list of endpoints from which the packages will be exported. |
| pull.items | Pull Items | `true` | `Integer` | `[1]` | number of subsequent pull requests to make |
| packageBuilder.target | Package Builder | `true` | `String` | `[(name=default)]` | The target reference for the DistributionPackageBuilder used to create distribution packages, e.g. use target=(name=...) to bind to services by name. |
| transportSecretProvider.target | Transport Secret Provider | `true` | `String` | `[(name=default)]` | The target reference for the DistributionTransportSecretProvider used to obtain the credentials used for accessing the remote endpoints, e.g. use target=(name=...) to bind to services by name. |
