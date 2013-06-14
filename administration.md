# Server administration guidelines

## General

* Always document all passwords, keys, paths, cronjobs, etc.
* No going live without decent documentation
* Never use `sendmail`
* Set up at least staging and production
* Freely add more environments
* Automatic incremental backups at least once a day
* Automatic full backups at least once a week
* Never allow `SSH` access via password
* Close all ports accept required ones (e.g. 80, 443 and 22)
* Use passwords with at least 30 characters
* No direct `root` access
* Set up a `deploy` user
* Enabled automatic security updates
* Set up availability checks using [Server Density](http://www.serverdensity.com),
  [Pingdom](https://www.pingdom.com) or [New Relic](http://newrelic.com)
* Freely add logging/monitoring
