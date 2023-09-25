simple mysqldump role
=====================


creates two shellscripts in the "mysql_mysqldump_directory":
- "mysql_mysqldump_shellscript_alldbs": dump all databases into one file (on demand) for backup-systems
- "mysql_mysqldump_shellscript_ringbuffer": dump databases (one per file) via cron and keep "mysql_mysqldump_ringbuffer_retention_days" days

see (defaults/main.yml)[defaults/main.yml] for all vars.
