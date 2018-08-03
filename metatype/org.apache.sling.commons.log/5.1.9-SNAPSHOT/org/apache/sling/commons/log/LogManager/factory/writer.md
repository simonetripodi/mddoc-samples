# Apache Sling Logging Writer Configuration

## `org.apache.sling.commons.log.LogManager.factory.writer`

Configure a Logger Writer for Sling Logging. See http://sling.apache.org/site/logging.html for more detailed documentation and description.

| ID  | Name | Required | Type | Default value | Description |
| --- | ---- | -------- | ---- | ------------- | ----------- |
| org.apache.sling.commons.log.file | Log File | `true` | `String` | `[logs/error.log]` | The name and path of the log file. If this is empty, logging goes to standard output (the console). If this path is relative it is resolved below ${sling.home}. |
| org.apache.sling.commons.log.file.number | Number of Log Files | `true` | `Integer` | `[5]` | The number of log files to keep. When the threshold of the log file reaches the configured maximum (see Log File Threshold), the log file is copied and a new log file is created. This setting specifies how many generations (incl. the active log file) should be kept. This is a positive numeric value. The default value is 5. If the Log File Threshold property specifies time/date controlled log file rotation, log file deletion can be disabled by setting the number of log files to '0'. Warning: setting this to a high number (more than 20) may be expensive on some file-systems, because all files need to be renamed when log files are rotated. |
| org.apache.sling.commons.log.file.size | Log File Threshold | `true` | `String` | `['.'yyyy-MM-dd]` | Controls the rotation of the log file by setting a maximum file size or a time/date schedule at which to rotate the log file. A size limit can be specified setting a pure number indicating the number of bytes or a number with a size indicator KB, MB, or GB (case is ignored). A time/date schedule can be specified as a java.util.SimpleDateFormat pattern. The default is "'.'yyyy-MM-dd" (daily log rotation). |
| org.apache.sling.commons.log.file.buffered | Buffered Logging | `true` | `Boolean` | `[false]` | By default logging events are immediately written to disk and will not be lost in case your application exits without properly closing appenders. If set to true  and if appenders are not closed properly when your application exits, then logging events not yet written to disk may be lost. See http://logback.qos.ch/manual/encoders.html#immediateFlush |
| webconsole.configurationFactory.nameHint | null | `true` | `String` | `[{org.apache.sling.commons.log.file}]` | null |
