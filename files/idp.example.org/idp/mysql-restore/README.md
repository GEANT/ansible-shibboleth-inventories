# IdP Database Restore

Put here the following files:

 * ```shibboleth-db.sql.gz```
 * ```statistics-db.sql.gz```

to be able to perform a database restoration.

These files are created by the script ```/etc/cron.daily/mysql-backup``` hosted on each IdP by default.
By default will be maintained only the last hour backup and stored into ```/var/local/backups/```.

After that you have to set the ```idp_db_restore``` to ```True``` to perform the restoration at next playbook execution.
