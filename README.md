MySQL-Backup-With-Cron
======================

This particualar cron job is for backing up all mysql databases using crontab schedualing and mysqldump, it then procedes to delete databases older then 14 days.

This cron job currently takes a copy of all mysql databases, to use this, the "username" and "password" will need to be changed. It currently uses -C to compress the input stream of the mysqldump from the server to the database and -A in order to dump --all-databases into the slected forlder.

Required to USE:
1. Change the username and password from "username" & "password"

Usefull chanages:
2. If choosen, change the backup directory.
3. If choosen, change the databases to backup.
