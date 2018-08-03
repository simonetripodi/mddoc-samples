# Apache Sling Distribution Packaging - Vault Package Builder Factory (`org.apache.sling.distribution.serialization.impl.vlt.VaultDistributionPackageBuilderFactory`)

OSGi configuration for vault package builders

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| webconsole.configurationFactory.nameHint | Property webconsole.configurationFactory.nameHint | `true` | `String` | `[Builder name: {name}]` | Description for webconsole.configurationFactory.nameHint |
| name | Name | `true` | `String` | `null` | The name of the package builder. |
| type | type | `true` | `String` | `[jcrvlt]` | The type of this package builder |
| importMode | Import Mode | `true` | `String` | `null` | The vlt import mode for created packages. |
| aclHandling | Acl Handling | `true` | `String` | `null` | The vlt acl handling mode for created packages. |
| package.roots | Package Roots | `true` | `String` | `null` | The package roots to be used for created packages. (this is useful for assembling packages with an user that cannot read above the package root) |
| package.filters | Package Node Filters | `true` | `String` | `null` | The package node path filters. Filter format: path|+include|-exclude |
| property.filters | Package Property Filters | `true` | `String` | `null` | The package property path filters. Filter format: path|+include|-exclude |
| tempFsFolder | Temp Filesystem Folder | `true` | `String` | `null` | The filesystem folder where the temporary files should be saved. |
| useBinaryReferences | Use Binary References | `true` | `Boolean` | `[false]` | If activated, it avoids sending binaries in the distribution package. |
| autoSaveThreshold | Autosave threshold | `true` | `Integer` | `[-1]` | The value after which autosave is triggered for intermediate changes. |
| cleanupDelay | The delay in seconds between two runs of the cleanup phase for resource persisted packages. | `true` | `Long` | `[60]` | The resource persisted packages are cleaned up periodically (asynchronously) since SLING-6503.The delay between two runs of the cleanup phase can be configured with this setting. 60 seconds by default |
| fileThreshold | File threshold (in bytes) | `true` | `Integer` | `[1]` | Once the data reaches the configurable size value, buffering to memory switches to file buffering. |
| MEGA_BYTES | The memory unit for the file threshold | `true` | `String` | `[MEGA_BYTES]` | The memory unit for the file threshold, Megabytes by default |
| useOffHeapMemory | Flag to enable/disable the off-heap memory | `true` | `Boolean` | `[false]` | Flag to enable/disable the off-heap memory, false by default |
| digestAlgorithm | The digest algorithm to calculate the package checksum | `true` | `String` | `[NONE]` | The digest algorithm to calculate the package checksum, Megabytes by default |
| monitoringQueueSize | The number of items for monitoring distribution packages creation/installation | `true` | `Integer` | `[0]` | The number of items for monitoring distribution packages creation/installation, 100 by default |
| pathsMapping | Paths mapping | `true` | `String` | `null` | List of paths that require be mapped.The format is {sourcePattern}={destinationPattern}, e.g. /etc/(.*)=/var/$1/some or simply /data=/bak |
| strictImport | Install a content package in a strict mode | `true` | `Boolean` | `[true]` | Flag to mark an error response will be thrown, if a content package will incorrectly installed |
