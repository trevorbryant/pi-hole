# pi-hole
Place to store pi-hole backup configurations.

The following live in `/etc/pihole`.
  * adlists.list
  * regex.list
  * setupVars.conf
  * whitelist.txt

This lives in `/etc/cron.weekly` for weekly upgrades.
  * upgrade

This can live anywhere and configured in crontab.
  * pihole-backup
