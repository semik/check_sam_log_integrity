# check_sam_log_integrity

Nagios plugin to verify Entrust SAM log integrity, main purpose is to monitor SAM server status.

Usage:

```
$ ./check_sam_log_integrity -H hostname -p 8082 -c cert.pem -k ~key.pem -b "eyJAdG/...TZEUSJ9Cg=="
OK - SAM: {"result":"valid"}
