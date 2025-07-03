# Scanner Detection Rules - SentinelOne

This repository contains Scanner detection rules for SentinelOne logs.

### Examples

Here are a few examples of the detections that are included in this repository:
- Agent Uninstalled From Multiple Hosts
- Process Memory Dumped Using ProcDump
- Unusual Ntdsutil Usage

### Event Sinks

When these detection rules are triggered, alerts are sent to the [event sinks](https://docs.scanner.dev/scanner/using-scanner/detection-rules/event-sinks)
in Scanner that are associated with these keys:
- `informational_severity_alerts`
- `low_severity_alerts`
- `medium_severity_alerts`
- `high_severity_alerts`
- `critical_severity_alerts`
- `fatal_severity_alerts`

### Deployment

To deploy these rules into your Scanner instance, you can follow the
instructions in the [Scanner documentation](https://docs.scanner.dev) under
**Detection Rules as Code**.
