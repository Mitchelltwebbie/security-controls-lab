\# CC-01: Security Logging and Monitoring



\## Control Objective

Ensure security-relevant events are logged and reviewable to support detection and investigation.



\## Scope

\- Windows 11 host system

\- Local user authentication events

\- System and application events



\## Control Description

The system generates logs for authentication, system, and application activity. Logs are retained locally and can be reviewed via Event Viewer for investigation and evidence.



\## Frequency

\- Logging: Continuous

\- Review: Ad hoc / during investigations



\## Evidence

\- Screenshots of Event Viewer logs

\- Exported log entries (when applicable)

\- Investigator notes



\## Owner

Mitch



\## Notes / Limitations

\- Local-only logs (no SIEM yet)

\- No centralized retention



