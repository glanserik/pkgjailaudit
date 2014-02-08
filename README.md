pkgjailaudit
============

A script for using the pkgng system in FreeBSD to monitor vulnerabilities in jails.

Put this script in /usr/local/periodic/security

Set the jails to be checked by periodic by adding them in a space separated list to the variable daily_status_security_pkgjailaudit_jaillist in /etc/periodic.conf

For example: daily_status_security_pkgjailaudit_jaillist="foo bar" tells the script to audit the jails foo and bar
