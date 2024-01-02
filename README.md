# DNSAddendumAgnostic - Microsoft.Windows.Server.DNS.Monitoring.Addendum v1.0.4.0

Download [here](https://github.com/theKevinJustin/DNSAddendumAgnostic/blob/main/Microsoft.Windows.Server.DNS.Monitoring.Addendum.xml)

### Microsoft.Windows.Server.DNS.Monitoring.Addendum
Microsoft.Windows.Server.DNS.Monitoring.Addendum - Management pack provides multiple capabilities, including: count logic monitors, daily summary report, alert closure/service/WMIvalidation recovery automation, and synthetic nslookup monitors.

#### Additional capabilities include:
ADI count logic monitors, daily summary report alerts of DNS alerts, daily alert closure automation, 
service recovery automation, synthetic internal/external nslookup check scoped to PDC emulators (versus all DNS servers), 
and WMI validation alert logic changes when Security tools randomly block WMI access.

Blog [https://kevinjustin.com/blog/2023/08/23/dns-addendum-pack/](https://kevinjustin.com/blog/2023/08/23/dns-addendum-pack/)

# Version History:
```
v1.0.4.0   4 Jan 2024 - Resolution State logic improvements for large environments
v1.0.3.9  27 Dec 2023 - Whitespace audit, ResolutionState changes, performance changes to DS/WA
v1.0.3.7  29 Aug 2023 - Updated for generic import, Discovery and Override GUIDs
v1.0.3.6  18 Jul 2023 - Updated alert severity
v1.0.3.5  27 Jun 2023 - ADI DNS count monitors for 3152,7616
v1.0.3.4  13 Jun 2023 - Additional overrides to disable rules, added count logic monitors on DNS events, reports to informational
v1.0.3.3   9 Jun 2023 - WA for nslookups, Recovery task for WMI validations, Query overload value changes CRIT/WARN
v1.0.3.3  31 Jan 2023 - Added ADI 404,408 count monitors, DNS internal/external powershell monitor
v1.0.3.2  23 Jan 2023 - Updated Cleanup methods with get modules, ADI count monitors
v1.0.2.9   5 Jan 2023 - ADI and DNS Server logging alerts set to warning
v1.0.2.7  15 Jul 2022 - MonitorTypes, Recovery Automation
v1.0.2.2  14 Jun 2022 - Updated run times
v1.0.1.5  18 Mar 2022 - Updated overrides to disable except for root DNS servers, additional logic
v1.0.1.4   8 Dec 2021 - Updated Proactive.DailyTasks.DNSAlerts.Report.Script.Alert.Rule to 1200
v1.0.0.11 18 Mar 2021 - Updated Tasks, script versions
v1.0.1.1  11 May 2021 - Updated Report datasource, moving report to front, updated monitors/alerts
v1.0.0.13 26 Mar 2021 - Added 'Windows DNS - Active Directory Integrated Write Failed' to autoclose rules
v1.0.0.9  16 Mar 2021 - Updated Daily Summary and autoclose reports
v1.0.0.6  10 Mar 2021 - Added DailySummary datasource, task, rules, alerts
v1.0.0.3   9 Mar 2021 - Updated property, delivered pack with daily report/task, recovery automation for EventID 4015
v1.0.0.0   8 Feb 2021 - Created for DNS server alert tuning
```
