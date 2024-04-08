# syslog
Syslog fork with the following breaking changes:
* `syslog.Dial()` exposes hostname as string argument
and non-breaking changes:
* new `syslog.DialTls()` method to make encrypted syslog calls
