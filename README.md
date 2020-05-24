# check_apt

## Usage

```bash
user$ bin/check_apt -h
This is a simple nagios check script for checking the apt status.

Syntax: check_apt [[[-w warning ] [-c critical] [-d days]] | [-h] | [-v]]
options:
-w | --warning        The number of updateable packages above which a warning is displayed (default: 10).
-c | --critical       The number of updateable packages above which a critical warning is displayed (default: 20).
-d | --days           The number of days before an update warning is displayed (default: 14).

-h | --help           Shows this help dialog.
-v | --version        Shows the version of this script.
```

```bash
user$ bin/check_apt
APT OK: 0 packages available for upgrade (0 critical updates).
```
