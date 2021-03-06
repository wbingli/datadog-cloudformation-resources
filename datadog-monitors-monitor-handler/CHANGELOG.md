# Changelog

# 2.0.0

Released on 2020-06-11

* Link to Resource: `s3://datadog-cloudformation-resources/datadog-monitors-monitor/datadog-monitors-monitor-2.0.0.zip`
* [BUGFIX] Don't try to set monitor id in the ReadHandler.
* [CHANGED] Removed attributes considered unused/unstable on the API side:
  * `MonitorOptions.Aggregation`
  * `MonitorOptions.DeviceIDs`
  * `MonitorStageGroup.LastDataTS`
  * `MonitorStateGroup.Message`
  * `MonitorStateGroup.TriggeringValue` (which was a reference to an also removed type `MonitorStateGroupValue`)

# 1.0.2

Released on 2019-11-21

* Link to Resource: `s3://datadog-cloudformation-resources/datadog-monitors-monitor/datadog-monitors-monitor-1.0.2.zip`
* [BUGFIX] Use `Double` for all previously `Float` values to get sufficient precision for high thresholds.

# 1.0.1

Released on 2019-11-19

* Link to Resource: `s3://datadog-cloudformation-resources/datadog-monitors-monitor/datadog-monitors-monitor-1.0.1.zip`
* [FEATURE] Add ApiURL property to allow managing resource in EU accounts

# 1.0.0

Released on 2019-11-18

* Link to Resource: `s3://datadog-cloudformation-resources/datadog-monitors-monitor/datadog-monitors-monitor-1.0.0.zip`
Initial release of the Datadog monitor resource for AWS CloudFormation.
