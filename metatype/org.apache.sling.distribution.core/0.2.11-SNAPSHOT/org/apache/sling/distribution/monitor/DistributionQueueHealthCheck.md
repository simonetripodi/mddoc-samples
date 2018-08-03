# Apache Sling Distribution Queue Health Check (`org.apache.sling.distribution.monitor.DistributionQueueHealthCheck`)

Description for org.apache.sling.distribution.monitor.DistributionQueueHealthCheck

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| hc.name | Name | `true` | `String` | `[SlingDistributionQueueHC]` | Health Check name |
| hc.tags | Tags | `true` | `String` | `null` | Health Check tags |
| hc.mbean.name | MBean name | `true` | `String` | `[slingDistributionQueue]` | Health Check MBean name |
| numberOfRetriesAllowed | Allowed retries | `true` | `Integer` | `[3]` | Number of allowed retries |
