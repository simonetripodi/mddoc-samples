# Apache Sling Distribution Importer - Local Package Importer Factory (`org.apache.sling.distribution.packaging.impl.importer.LocalDistributionPackageImporterFactory`)

Description for org.apache.sling.distribution.packaging.impl.importer.LocalDistributionPackageImporterFactory

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Importer name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the importer. |
| packageBuilder.target | Package Builder | `true` | `String` | `[(name=default)]` | The target reference for the DistributionPackageBuilder used to create distribution packages, e.g. use target=(name=...) to bind to services by name. |
