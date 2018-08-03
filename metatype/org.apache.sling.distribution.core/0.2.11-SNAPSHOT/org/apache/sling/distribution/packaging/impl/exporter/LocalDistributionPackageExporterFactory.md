# Apache Sling Distribution Exporter - Local Package Exporter Factory (`org.apache.sling.distribution.packaging.impl.exporter.LocalDistributionPackageExporterFactory`)

Description for org.apache.sling.distribution.packaging.impl.exporter.LocalDistributionPackageExporterFactory

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Exporter name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the exporter. |
| packageBuilder.target | Package Builder | `true` | `String` | `null` | The target reference for the DistributionPackageBuilder used to create distribution packages, e.g. use target=(name=...) to bind to services by name. |
