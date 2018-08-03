# Apache Sling Logging Logger Configuration (`org.apache.sling.commons.log.LogManager.factory.config`)

Configure Loggers with levels, pattern and destination. See http://sling.apache.org/site/logging.html for more detailed documentation and description.

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| org.apache.sling.commons.log.level | Log Level | `true` | `String` | `[info]` | Root Logger log level setting. |
| org.apache.sling.commons.log.file | Log File | `true` | `String` | `[logs/error.log]` | The name and path of the log file. If this is empty, logging goes to standard output (the console). If this path is relative it is resolved below ${sling.home}. |
| org.apache.sling.commons.log.pattern | Message Pattern | `true` | `String` | `[{0,date,dd.MM.yyyy HH:mm:ss.SSS} *{4}* [{2}] {3} {5}]` | Message Pattern for formatting the log messages. For complete details refer to http://logback.qos.ch/manual/layouts.html#ClassicPatternLayout |
| org.apache.sling.commons.log.names | Logger | `true` | `String` | `null` | The logger names applicable for this logger configuration. Each logger name applies for any child category unless configured otherwise. E.g. a logger name of org.apache.sling applies to logger org.apache.sling.commons unless there is a different configuration for org.apache.sling.commons. |
| webconsole.configurationFactory.nameHint | null | `true` | `String` | `[{org.apache.sling.commons.log.file}: {org.apache.sling.commons.log.level}]` | null |
| org.apache.sling.commons.log.additiv | Additivity | `true` | `Boolean` | `null` | If set to false then logs from these loggers would not be sent to any appender attached higher in the hierarchy |
