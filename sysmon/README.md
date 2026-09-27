# Sysmon

Sysmon provides richer Windows endpoint telemetry for the SOC lab.

Before applying a configuration, validate the installed version and schema:

    C:\Tools\Sysmon\Sysmon64.exe -?
    C:\Tools\Sysmon\Sysmon64.exe -s

The final configuration will be added after the installed schema is confirmed.

Wazuh can collect the Microsoft-Windows-Sysmon/Operational event channel.
