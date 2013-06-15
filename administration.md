# Server administration guidelines

* Always document all ports, passwords, keys, application paths, configuration files, cronjobs, etc.
* No going live without decent documentation
* Never use `sendmail`
* Set up at least staging and production environment
* Freely add more environments
* Automatic incremental backups at least once a day
* Automatic full backups at least once a week
* Never allow `SSH` access via password
* Close all ports accept required ones (e.g. 22, 80 and 443)
* Use passwords with at least 30 characters
* No direct `root` access
* Set up a `deploy` user
* Enable automatic security updates
* Set up availability checks using [Server Density](http://www.serverdensity.com),
  [Pingdom](https://www.pingdom.com) or [New Relic](http://newrelic.com)
* Redirect 301 from `domain.com` to `www.domain.com` permanently
* Offline documentation if it makes sense
* Freely add logging/monitoring/log checks
* Every server should be accessible by at least two people/organisations
* Use an appropriate log level, don't clutter the logs with unnecessary data
