# Bash backup script for databases

This script is designed to be (and remain) relatively simple. This script creates a backup of one or multiple databases, using differents login/password for each database. It's not for a system administrator, I designed it to be used by webmaster, to create backup in a shared hosting environnement with a cron job for instance.

The backups generated by this script can be compressed and sent to another place by FTP. If the backups are sent by FTP, it will checked the files exists on the FTP.
