# Apache Sling Distribution Packaging - Package Builder Factory (`org.apache.sling.distribution.serialization.impl.DistributionPackageBuilderFactory`)

OSGi configuration for package builders

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Builder name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the package builder. |
| type | type | `true` | `String` | `[resource]` | The persistence type used by this package builder |
| format.target | Content Serializer | `true` | `String` | `[(name=default)]` | The target reference for the DistributionSerializationFormat used to (de)serialize packages, e.g. use target=(name=...) to bind to services by name. |
| tempFsFolder | Temp Filesystem Folder | `true` | `String` | `null` | The filesystem folder where the temporary files should be saved. |
| fileThreshold | File threshold | `true` | `Integer` | `[1]` | Once the data reaches the configurable size value, buffering to memory switches to file buffering. |
| memoryUnit | The memory unit for the file threshold | `true` | `String` | `[MEGA_BYTES]` | The memory unit for the file threshold, Megabytes by default |
| useOffHeapMemory | Flag to enable/disable the off-heap memory | `true` | `Boolean` | `[false]` | Flag to enable/disable the off-heap memory, false by default |
| digestAlgorithm | The digest algorithm to calculate the package checksum | `true` | `String` | `[NONE]` | The digest algorithm to calculate the package checksum, Megabytes by default |
| monitoringQueueSize | The number of items for monitoring distribution packages creation/installation | `true` | `Integer` | `[0]` | The number of items for monitoring distribution packages creation/installation, 100 by default |
| cleanupDelay | The delay in seconds between two runs of the cleanup phase for resource persisted packages. | `true` | `Long` | `[60]` | The resource persisted packages are cleaned up periodically (asynchronously) since SLING-6503.The delay between two runs of the cleanup phase can be configured with this setting. 60 seconds by default |
| package.filters | Package Node Filters | `true` | `String` | `null` | The package node path filters. Filter format: path|+include|-exclude |
| property.filters | Package Property Filters | `true` | `String` | `null` | The package property path filters. Filter format: path|+include|-exclude |
