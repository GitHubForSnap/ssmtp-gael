# [ssmtp-gael](https://snapcraft.io/ssmtp-gael)

Extremely simple MTA to get mail off the system to a mail hub

A secure, effective and simple way of getting mail off a system to your mail hub. It contains no suid-binaries or other dangerous things - no mail spool to poke around in, and no daemons running in the background. Mail is simply forwarded to the configured mailhost. Extremely easy configuration.

**Usage**

* Configure ssmtp
```
sudo vi /var/snap/ssmtp-gael/current/ssmtp.conf
```

* Create aliases (if needed)
```
sudo snap alias ssmtp-gael.ssmtp ssmtp
sudo snap alias ssmtp-gael.ssmtp sendmail
sudo snap alias ssmtp-gael.ssmtp mailq
```

**2021-08-03**
* New build to resolve CVE-2021-20231/CVE-2021-20232/USN-5029-1

**2021-04-24**
* Initial release
