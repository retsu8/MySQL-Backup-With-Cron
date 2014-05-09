MySQL-Backup-With-Cron
======================

This particualar cron job is for backing up all mysql databases using crontab schedualing and mysqldump, it then procedes to delete databases older then 14 days.

This cron job currently takes a copy of all mysql databases, to use this, the "username" and "password" will need to be changed. It currently uses -C to compress the input stream of the mysqldump from the server to the database and -A in order to dump --all-databases into the slected forlder.

Required: <br>
1. mkdir /root/databaseBackups <br>
2. Change the username and password from "username" & "password" <br>
 
Usefull: <br>
1. If choosen, change the backup directory. <br>
2. If choosen, change the databases to backup.
